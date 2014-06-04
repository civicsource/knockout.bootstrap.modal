#Knockout Bootstrap Modal Binding

> A simple knockout binding that wraps Bootstrap's modal.

##Install with [Bower](http://bower.io/)

```
bower install knockout-bootstrap-modal
```

Then add `knockout.bootstrap.modal.js` to your project. If you are using AMD, also be sure to alias in your requirejs config `modal.js` from Bootstrap as `bootstrap.modal.js`:

```js
requirejs.config({
    paths: {
        'bootstrap.modal': 'bower_components/bootstrap/js/modal'
    }
});
```

##How to Use

Include the script on your page (either via a normal script tag or via an AMD loader). Then bind it to an element:

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