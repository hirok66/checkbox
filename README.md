<div class="mb-3 text-right   delll-btn d-none">
                            <button type="submit"  class="btn btn-danger cat " >delete Check</button>
                        </div>

                        //////////////////////////////////
                             <th>
                              <div class="form-check">
                                        <label class="form-check-label">
                                            <input type="checkbox"  id="checkAll" class="form-check-input checkAll">
                                            Checked All
                                        <i class="input-frame"></i></label>
                                    </div>
                                </th>
                                /////////////////
                                <td>
                                     <div class="form-check">
                                         <label class="form-check-label">
                                             <input type="checkbox"  name="category_id[]" value="{{ $category->id }}"  class="form-check-input checkAll">
                                            <i class="input-frame"></i></label>
                                             </div>
                                               </td>
                                               ///////////////////////////////


                                               
<script>
    $("#checkAll").click(function(){

    $('input:checkbox').not(this).prop('checked', this.checked);
});
    $(".checkAll").click(function(){
        $('.delll-btn').removeClass('d-none');

});
</script>
