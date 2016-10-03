# Knockout Bootstrap Modal Binding

> A simple knockout binding that wraps Bootstrap's modal.

## Installation

```
npm install knockout.bootstrap.modal
```

Then add `knockout.bootstrap.modal.js` to your project.


## Usage

```html
<div role="dialog" aria-hidden="true" class="modal fade" data-bind="modal: { show: isPopupOpen }">
	<div class="modal-dialog modal-lg">
		<div class="modal-content">
			<div class="modal-header">
				<button type="button" class="close" data-dismiss="modal" title="Close" aria-label="Close">&times;</button>
				<h4 class="modal-title">My Modal</h4>
			</div>

			<div class="modal-body">
				Lorem ipsum dolor…
			</div>

			<div class="modal-footer">
				<button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
				<button type="button" class="btn btn-primary">Save</button>
			</div>
		</div>
	</div>
</div>
```