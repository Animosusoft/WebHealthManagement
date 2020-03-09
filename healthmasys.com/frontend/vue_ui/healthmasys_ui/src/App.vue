<script>
import axiox from 'axios';

export default {
  name: 'app',
  data() {
    return {
      form: {
        firstname: '',
        lastname: '',
        email: '',
        phonenumber: '',
        birthday: '',
        'Identification Type': '',
        ID: '',
      },
    };
  },
  methods: {
    onSubmit() {
      console.log('Click');
      if (!this.form.formIsValid) return;
      axiox
        .post('');
      console.log('Send my form !');
    },
  },
  computed: {
    formIsValid() {
      return (
        this.form.firstname.length > 0
        && this.form.lastname.length > 0
        && this.form.email.length > 0
        && (this.form.phonenumber > 0 && this.form.phonenumber < 10)
      );
    },
  },
};
</script>

<template>
    <div id="app" class="container py-4">
        <div class="row">
            <div class="col-12">
                <form @submit.prevent="onSubmit()">
                    <div class="form-group">
                        <label>First Name :</label>
                        <input type="text" name="firstname" class="form-control"
                        placeholder="First name" required autofocus
                        v-model="form.firstname">
                    </div>
                    <div class="form-group">
                        <label>Last Name :</label>
                        <input type="text" name="lastname" class="form-control"
                        placeholder="Last name" required v-model="form.lastname">
                    </div>
                    <div class="form-group">
                        <label>Email :</label>
                         <div class="input-group mb-3">
                    <input type="email" name="email" class="form-control"
                     placeholder="Your Email" v-model="form.email">
                        <div class="input-group-append">
                        <span class="input-group-text">@example.com</span>
                        </div>
                    </div>
                    </div>
                    <div class="form-group">
                        <label>Phone Number :</label>
                        <input type="tel" name="phonenumber" class="form-control"
                        placeholder="0XX-XXX-XXXX" required
                        v-model="form.phonenumber"
                        pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" title="Please match
                        the pattern {0XX}-{XXX}-{XXXX}">
                    </div>
                    <div class="form-group">
                        <label>Birthday :</label>
                        <input type="date" name="birthday" class="form-control"
                        required v-model="form.birthday">
                    </div>
                    <div class="form-group">
                        <label>ID</label>
                        <div class="input-group mt-3 mb-3">
                        <button type="button" class="btn btn-outline-secondary dropdown-toggle"
                            data-toggle="dropdown"> Identification </button>
                        <select class="form-control" name="Identification Type"
                            v-model="form.id_type">
                           <option value="Knust Student ID" selected>Knust Student ID</option>
                           <option value="National Health Insurance">National Health Insurance
                           </option>
                           <option value="Driver Licenses">Driver License</option>
                        </select>
                        <div class="form-control">
                        <input type="text" name="ID" placeholder="ID" required
                        vmv-model="form.id_number">
                        </div>
                        </div>
                    </div>
                    <div class="form-group">
                    <button type="submit" class="btn btn-primary">Submit</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>
