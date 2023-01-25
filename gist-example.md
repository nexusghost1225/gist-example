regex email validator

expression: ^\w+@[a-zA-Z_]+?\.[a-zA-Z]{2,3}$

^ is an anchor operator to render the beginning of the expression
$ is an anchor operator to render the ending of the expression

\w+ validates that the adress contains only letters beore the @ symbol

[a-zA-Z_]+?\.[a-zA-Z]{2,3} validates lower case and upper case values

expression does not support multiple &qout

allowed examples: joe@aol.com Paul@gov.com

not-allowed: Joes@uk.co.com paul@us.co.gov