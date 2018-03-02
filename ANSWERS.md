## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

The value of the test field tag. IE. the initial value of the field.


2. Go to `localhost:3000/teachers` in your browser; why does this not work?

 This page is made upon creation. Thus it does not exist before posting

3. What type of request did your browser just perform?
 GET and POST

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

ended up at  localhost:3000/teachers/

5. Why does `localhost:3000/teachers` work now?
It works because a POST request creates the page /teachers and upon submitting it forces you to land on the temporary page.
