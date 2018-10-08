<template>
  <div class="container">
    <form>
      <div class="row">
        <div class="col-xs-2 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
          <h1>File a Complaint</h1>
          <hr>
          <div class="form-group">
            <label for="email">Mail</label>
            <input type="text" id="email" class="form-control">
          </div>
          <div class="form-group">
            <label for="password">Password</label>
            <input type="password" id="password" class="form-control">
          </div>
          <div class="form-group">
            <label for="age">Age</label>
            <input type="age" id="age" class="form-control">
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3 form-group">
          <label for="message">Message</label>
          <!-- Interpolation between <textarea>{{ test }}</textarea> doesn't work -->
          <textarea id="message" rows="5"></textarea>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
          <div class="form-group">
            <label for="sendMail">
              <input type="checkbox" id="sendMail" value="SendMail"> Send Mail
            </label>
            <label for="sendInfoMail">
              <input type="checkbox" id="sendInfoMail" value="SendMail"> Send InfoMail
            </label>  <!-- Also show for single checkbox with true/false -->
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3 form-group">
            <label for="male">
              <input type="radio" id="male" value="Male">
              Male
            </label>
            <label for="female">
              <input type="radio" id="female" value="Male">
              Female
            </label>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3 form-group">
          <label for="priority">Priority</label>
          <select id="priority" class="form-group">
            <option></option>
          </select>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-xs-12 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
          <button class="btn btn-primary" >Submit!</button>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {}
</script>

<style>
</style>
