<h1>                                                                    Terraform Variables</h1>
<li>
  <ul>Variables are placeholders for values that can be used in your configuration</ul>
  <ul>They make your code more dynamic and adaptable to different environments or use cases.</ul>
  <ul>They allow you to set values that can be reused throughout your Terraform code and changed without modifying the code itself</ul>
</li>

<h2>Defining Variables</h2>
<li>
<ul>  variable  "example_variable" {</ul>
<ul>     description = "This is an example variable"</ul>
<ul>     type        = string</ul>
<ul>     default     = "default value"</ul>
<ul>}</ul>
</li>
