<template>
  <div style="text-align: left;">
    <div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true" >
      <div class="modal-dialog" role="document">
        <div class="modal-content">
          <div class="modal-header">
            <h4 class="modal-title" id="exampleModalLabel">Sign in</h4>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
          <div class="modal-body">
            <form>
              <div class="form-group">
                <label for="email" class="col-form-label">Email address:</label>
                <input type="email" class="form-control" name="email" placeholder="Enter email" required="">
              </div>
              <div class="form-group">
                <label for="password" class="col-form-label">Password:</label>
                <input type="password" class="form-control" name="password1" placeholder="Enter password" required="">
              </div>
            </form>
          </div>
          <div class="modal-footer">
            <button type="button" class="btn btn-primary">sign in</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
