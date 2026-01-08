1. In one sentence: What does res.render(view, data) do?
: It takes the EJS view file and the data you give, puts them together, and sends the final HTML page to the user

2. What is the difference between <%= %> and <%- %>?
: <%= %> shows the value as normal text (escapes HTML), but <%- %> shows the value as real HTML (does not escape)

3. Where does Express look for EJS templates (folder path)?
: Express looks for EJS template files in the folder set by app.set('views', ...), usually called views/