# freetext



<button type="button" name="btnLink" id="btnLink">Open Pop</button>

<div class="modal fade" id="ModalPopUp" role="dialog">
    <div class="modal-dialog err-pop" style="">
        <div class="modal-content">
            <div class="modal-header">
                <button id="DivClose" type="button" class="close" data-dismiss="modal">&times;</button>
            </div>
            <div class="modal-body" style="text-align:center;">
                Are you sure you want to submit
                @Html.ActionLink("Yes", "Create", "EmployMVC")

                @Html.ActionLink("No", "Somemethod", "EmployMVC")


            </div>
        </div>
    </div>
</div>
<script src="~/Scripts/jquery-3.3.1.js"></script>
@*<script src="https://code.jquery.com/jquery-1.10.0.min.js"
        integrity="sha256-2+LznWeWgL7AJ1ciaIG5rFP7GKemzzl+K75tRyTByOE="
        crossorigin="anonymous"></script>*@
<script>
    $("#btnLink").click(function () {
        $('#ModalPopUp').modal('show');
    })
</script>



<button type="button" name="btnLink" id="btnLink">Open Pop</button>

<div class="modal fade" id="ModalPopUp" role="dialog">
    <div class="modal-dialog err-pop" style="">
        <div class="modal-content">
            <div class="modal-header">
                <button id="DivClose" type="button" class="close" data-dismiss="modal">&times;</button>
            </div>
            <div class="modal-body" style="text-align:center;">
                Are you sure you want to submit
                @Html.ActionLink("Yes", "Create", "EmployMVC")

                @Html.ActionLink("No", "Somemethod", "EmployMVC")


            </div>
        </div>
    </div>
</div>
<script src="~/Scripts/jquery-3.3.1.js"></script>
@*<script src="https://code.jquery.com/jquery-1.10.0.min.js"
        integrity="sha256-2+LznWeWgL7AJ1ciaIG5rFP7GKemzzl+K75tRyTByOE="
        crossorigin="anonymous"></script>*@
<script>
    $("#btnLink").click(function () {
        $('#ModalPopUp').modal('show');
    })
</script>
