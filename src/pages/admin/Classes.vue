<template>
    <div>
        <Breadcrumbs title="Classes"/>
        <!-- Container-fluid starts-->
        <div class="container-fluid">
            <div class="row">
              <div class="col-md-12">
                <div class="card">
                    <div class="card-header">
                      <h5>Update Class</h5><span>lorem ipsum dolor sit amet, consectetur adipisicing elit</span>
                    </div>
                    <div class="card-body">
                      <table class="table">
                        <thead>
                          <tr>
                            <th>
                              select all
                            </th>
                            <th>Class Name</th>
                            <th>Arm</th>
                            <th>Description</th>
                            <th></th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td><input type="checkbox" name="" class="form-check" id="" checked></td>
                            <td>
                              <input type="text" class="form-control" :value="'JS 1'" disabled>
                            </td>
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            <td>
                              <div class="form-group">
                                <button class="btn btn-primary btn-sm"> + add</button>
                                </div>
                            </td>
                          </tr>

                          <tr>
                            <td><input type="checkbox" name="" class="form-check" id="" checked></td>
                            <td>
                              <input type="text" class="form-control" :value="'JS 2'" disabled>
                            </td>
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            <td>
                              <div class="form-group">
                                <button class="btn btn-primary btn-sm"> + add</button>
                                </div>
                            </td>
                          </tr>


                        </tbody>
                      </table>
                    </div>
                </div>
              </div>               
            </div>
        </div>
        <!-- Container-fluid Ends-->
    </div>
</template>

<script>
export default {
}
</script>