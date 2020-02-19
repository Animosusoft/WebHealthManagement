<template>
    <div id="app" class="container py-4">
        <div class="row">
            <div class="col-12">
                <form>
                    <div class="form-group">
                        <label>First Name :</label>
                        <input type="text" name="firstname" class="form-control"
                        placeholder="First name" required autofocus>
                    </div>
                    <div class="form-group">
                        <label>Last Name :</label>
                        <input type="text" name="lastname" class="form-control"
                        placeholder="Last name" required>
                    </div>
                    <div class="form-group">
                        <label>Email :</label>
                         <div class="input-group mb-3">
                    <input type="email" class="form-control" placeholder="Your Email">
                        <div class="input-group-append">
                        <span class="input-group-text">@example.com</span>
                        </div>
                    </div>
                    </div>
                    <div class="form-group">
                        <label>Phone Number :</label>
                        <input type="tel" name="phonenumber" class="form-control"
                        placeholder="Phone Number" required
                        pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" title="Three letter country code">
                    </div>
                    <div class="form-group">
                        <label>Birthday :</label>
                        <input type="date" name="birthday" class="form-control" required>
                    </div>
                    <div class="form-group">
                        <label>ID</label>
                        <div class="input-group mt-3 mb-3">
                        <button type="button" class="btn btn-outline-secondary dropdown-toggle"
                            data-toggle="dropdown"> Identification </button>
                        <select class="form-control" name="Identification Type">
                           <option value="Knust Student ID" selected>Knust Student ID</option>
                           <option value="National Health Insurance">National Health Insurance
                           </option>
                           <option value="Driver Licenses">Driver License</option>
                        </select>
                        <div class="form-control">
                        <input type="text" name="ID" placeholder="ID" required>
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

<script>
export default {
  name: 'app',
};
</script>
