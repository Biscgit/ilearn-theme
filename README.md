# iLearn Theme

Theming of the iLearn Portal's Landing page through JavaScript.

## How to Setup

1. Within iLearn, click on edit, create a new `Textblock`.
2. Move the `Textblock` to the bottom. Ensure that it is the last element, because of the execution order.
3. On the `Textblock`, go to configure and click the expander on the content section.
4. Enable `HTML` (click on the `</>`-Button).
5. In the content-field, paste:
    ```html
    <script>
        
    </script>
    ```
6. Paste the contents of `ilearn.js` between the `<script>` Tags.
7. Optionally, adjust the background or colors with the variables available at the top of the file.
   The username gets fetched automatically from the HTML source.
8. Save changes
9. Move the "Favourite Courses" widget to the top, to apply the right offset.
10. Disable edit mode and enjoy!
