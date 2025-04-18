<p align="center">
  <h1 align="center">Divination API</h1>
  <p align="center">An API for fetching Magic: The Gathering's Comprehensive Rules</p>
</p>

> “Half of your studies will be learning the laws of magic. The other half will be bending them.”
> —Naru Meha, master wizard

A .NET Core API service that enables easy, quick searching of Magic: The Gathering's Comprehensive Rules.
This service provides the following endpoints:

- `/divination/rules/{index}` -> Find rule via index
- `/divination/rules/search?query={}` -> Find rule via text query
- `/divination/glossary` -> Get all glossary entries
- `/divination/glossary/search?query={}` -> Find an entry in the glossary via text query

For more information, take a look at the [Swagger docs](https://api.cardspy.nz/divination).

<p align="center">
  <img src="divination.jpg" height="250" />
  <p align="center"><i>Divination by Matt Stewart</i></p>
</p>
