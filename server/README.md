# Welcome to GraphiQL
#
# GraphiQL is an in-browser tool for writing, validating, and
# testing GraphQL queries.
#
# Type queries into this side of the screen, and you will see intelligent
# typeaheads aware of the current GraphQL type schema and live syntax and
# validation errors highlighted within the text.
#
# GraphQL queries typically start with a "{" character. Lines that starts
# with a # are ignored.
#
# An example GraphQL query might look like:
#
#     {
#       field(arg: "value") {
#         subField
#       }
#     }
#
# Keyboard shortcuts:
#
#  Prettify Query:  Shift-Ctrl-P (or press the prettify button above)
#
#       Run Query:  Ctrl-Enter (or press the play button above)
#
#   Auto Complete:  Ctrl-Space (or just start typing)
#

{
  book(id: "5cce8860cf182a17fbfdbd24") {
    _id
    isbn
    title
    author
    description
    published_year
    publisher
    updated_date
  }
}

# mutation {
#   addBook(
#     isbn: "12345678",
#     title: "Whatever this Book Title",
#     author: "Mr. Bean",
#     description: "The short explanation of this Book",
#     publisher: "Djamware Press",
#     published_year: 2019
#   ) {
#     updated_date
#   }
# }

# mutation {
#   updateBook(
#     id: "5cce8860cf182a17fbfdbd24",
#     isbn: "12345678221",
#     title: "The Learning Curve of GraphQL",
#     author: "Didin J.",
#     description: "The short explanation of this Book",
#     publisher: "Djamware Press",
#     published_year: 2019
#   ) {
#     _id,
#     updated_date
#   }
# }

# mutation {
#   removeBook(id: "5c75455b146dbc2504b94012") {
#     _id
#   }
# }