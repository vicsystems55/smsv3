<template>
    <div>
        <Breadcrumbs title="Courses"/>
        <!-- Container-fluid starts-->
        <div class="container-fluid">
            <div class="row">
              <div class="col-md-12">
                                <div class="card">
                    <div class="card-header">
                      <h5>Update Courses</h5><span>lorem ipsum dolor sit amet, consectetur adipisicing elit</span>
                    </div>
                    <div class="card-body">
                      <table class="table">
                        <thead>
                          <tr>
                            <th>
                              select all
                            </th>
                            <th>Course Name</th>
                            <th>Description</th>
                            
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td><input type="checkbox" name="" class="form-check" id="" checked></td>
                            <td>
                              <input type="text" class="form-control" :value="'Mathematics'" disabled>
                            </td>
                            
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            
                          </tr>

                          <tr>
                            <td><input type="checkbox" name="" class="form-check" id="" checked></td>
                            <td>
                              <input type="text" class="form-control" :value="'English'" disabled>
                            </td>
                            
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            
                          </tr>

                          <tr>
                            <td><input type="checkbox" name="" class="form-check" id="" checked></td>
                            <td>
                              <input type="text" class="form-control" :value="'Biology'" disabled>
                            </td>
                            
                            <td>
                              <input type="text" class="form-control">
                            </td>
                            
                          </tr>

                          <tr>
                            <td><input type="checkbox" name="" class="form-check" id="" checked></td>
                            <td>
                              <input type="text" class="form-control" :value="'Chemistry'" disabled>
                            </td>
                            
                            <td>
                              <input type="text" class="form-control">
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