<div class="modal fade" id="newEntry" tabindex="-1">
    <div class="modal-dialog modal-dialog-centered modal-dialog-scrollable">
   	 <div class="modal-content">
   		 <div class="modal-header">
   			 <h5 class="modal-title">New Entry</h5>
   			 <button type="button" class="btn-close" data-bs-dismiss="modal" />
   		 </div>

   		 <div class="modal-body">
   			 <!-- Add Modal Content here -->
   		 </div>

   		 <div class="modal-footer">
   			 <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Cancel</button>
   			 <button type="button" class="btn btn-primary">Add</button>
   		 </div>
   	 </div>
    </div>
</div>

<!-- Date Input -->
<div class="row">
    <div class="col">
   	 <form class="form-floating">
   		 <input type="number" class="form-control" id="dayInput" value="1" min="1" max="31"/>
   		 <label for="dayInput">Day</label>
   	 </form>
    </div>
    <div class="col">
   	 <form class="form-floating">
   		 <input type="number" class="form-control" id="monthInput" value="1" min="1" max="12"/>
   		 <label for="monthInput">Month</label>
   	 </form>
    </div>
    <div class="col">
   	 <form class="form-floating">
   		 <input type="number" class="form-control" id="yearInput" value="2021" min="2021" />
   		 <label for="yearInput">Year</label>
   	 </form>
    </div>
</div>