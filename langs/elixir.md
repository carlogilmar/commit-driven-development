# Guideline for Elixir 

Consider this approach is considering you're using a [mix](https://hexdocs.pm/mix/Mix.html) project. This is just a simple guide for novice developers starting their journey in the BEAM world.

## Tooling 

- [Mix](https://hexdocs.pm/mix/Mix.html)
- [Credo](https://github.com/rrrene/credo)
- [Dialyxir](https://github.com/jeremyjh/dialyxir)

## Considerations 

- Run often `mix format` to format your code and commit this.
- Run credo to make the code analysis before to push your code, if there are warnings fix it and commit this.
- Run dialyzer before push your code to run the code analysis, if there are warning or errors fix it.

## Example

```
* c92872d  1 year, 11 months ago Carlo Gilmar Moving files into core directory
* b75d1b4  1 year, 11 months ago Carlo Gilmar Implement scheduler in StoryClient and update tests
* 805ef43  1 year, 11 months ago Carlo Gilmar Adding credo suggestions in tests
* 05f50f5  1 year, 11 months ago Carlo Gilmar Running mix formatter
* 792b348  1 year, 11 months ago Carlo Gilmar Implement get_stories/1 and test as pagination fetch in StoryClient
* c9f5ca1  1 year, 11 months ago Carlo Gilmar Implement get_top_50/0 and fetch_top_50/0 and tests in story client
* 3fc460c  1 year, 11 months ago Carlo Gilmar Adding test for StoryClient and implement get_story/1 into a genserver
* 07b05e9  1 year, 11 months ago Carlo Gilmar Implement Task.async_stream when get the stories detail
* 04e8923  1 year, 11 months ago Carlo Gilmar Adding test and rename it, and implement HackerNewsClient.get_stories/0
* 4a2bc14  1 year, 11 months ago Carlo Gilmar Adding unit test and implementation of HackerNewsClient.get_story_detail/1
* e4456e5  1 year, 11 months ago Carlo Gilmar Adding credo, config file and applying suggestions
* e437604  1 year, 11 months ago Carlo Gilmar Adding HackerNewsClient and unit test for get_top_ids/0 and http client mock
* bae3c61  1 year, 11 months ago Carlo Gilmar Adding config file and test configuration
* 860e3c5  1 year, 11 months ago Carlo Gilmar Adding deps and http_client for implement get/1
* 424c174  1 year, 11 months ago Carlo Gilmar First commit, dear college have a nice day reviewing my code :)

```
