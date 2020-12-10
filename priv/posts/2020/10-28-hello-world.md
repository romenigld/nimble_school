%{
  title: "Hello World!",
  author: "Romenig Lima Damasio",
  tags: ~w(hello),
  description: "Our first blog post is here",
  published: true
}
---
Body of the "Hello world" article.

This is a *markdown* document with support for code highlighters:

```elixir
IO.puts "hello world".
iex> 1+2
3

iex> 1/0
** (ArithmeticError) bad argument in arithmetic expression
    :erlang./(1, 0)


iex> changeset = User.changeset(%User{}, %{})
#Ecto.Changeset<action: nil, changes: %{},
  errors: [name: {"can't be blank", [validation: :required]},
   email: {"can't be blank", [validation: :required]},
   bio: {"can't be blank", [validation: :required]}],
  data: #Hello.User<>, valid?: false>
```