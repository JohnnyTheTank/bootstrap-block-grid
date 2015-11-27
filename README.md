# bootstrap-block-grid
real block grid for bootstrap (3.x & 4.x)

## demo
[demo on plnkr](http://plnkr.co/edit/qkyOlC?p=preview)

## usage

1. Install:
    1. via [bower](http://bower.io/)
        `bower install --save bootstrap-block-grid`

    2. via downloaded files

2. Add files to your html
    1. when using bower
    ```html
    <!-- bootstrap 3 -->
    <script src="bower_components/bootstrap-block-grid/dist/bootstrap3-block-grid.min.css"></script>

    <!-- bootstrap 4 -->
    <script src="bower_components/bootstrap-block-grid/dist/bootstrap4-block-grid.min.css"></script>
    ```

    2. when using downloaded files
    ```html
    <!-- bootstrap 3 -->
    <script src="bootstrap3-block-grid.min.css"></script>

    <!-- bootstrap 4 -->
    <script src="bootstrap4-block-grid.min.css"></script>
    ```

3. Sample Markup

    ```html
    <div class="block-grid-xs-2 block-grid-sm-3 block-grid-md-4">
        <div>
            Content 1
        </div>
        <div>
            Content 2
        </div>
        <div>
            Content 3
        </div>
        <div>
            Content 4
        </div>
        <div>
            Content 5
        </div>
        <div>
            Content 6
        </div>
    </div>
    ```

## available classes

- *xs*
    - `block-grid-xs-1`
    - `block-grid-xs-2`
    - ...
    - `block-grid-xs-12`
- *sm*
    - `block-grid-sm-1`
    - `block-grid-sm-2`
    - ...
    - `block-grid-sm-12`
- *md*
    - `block-grid-md-1`
    - `block-grid-md-2`
    - ...
    - `block-grid-md-12`
- *lg*
    - `block-grid-lg-1`
    - `block-grid-lg-2`
    - ...
    - `block-grid-lg-12`


# licence
MIT
