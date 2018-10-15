+ There are several frontend frameworks like Bootstrap, Foundation, YAML etc.

+ bootstrap.min.css is added in the head of the html. This is because they take less space and can be downloaded faster.

+ grid system of bootstrap : Rows should be inside a container and a column has to be inside a row.

+ .img-responsive (now .img-fluid) is used to create responsive images

+ Our customized ``` styles.css ``` should be linked below ``` bootstrap ```.

+ For adding modals, include the jquery script as well as bootstrap.min.js in the header.

+ To Add a modal to an image : ```<img class="img-responsive" src="images/555.jpeg" data-toggle="modal" data-target="#project1">```

+ Add the following code just before the closing body tag for defining the modal.
``` 
<!-- Modal -->
    <div class="modal fade" id="project1" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h4 class="modal-title" id="myModalLabel">Favorite App Page</h4>
                </div>
                <div class="modal-body">
                    <img class="img-responsive" src="images/555.jpeg">
                    This was my first project in this class. I learned a lot about HTML and CSS.
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>
```
