require 'github_changelog_generator/task'

TOKEN = ENV["CHANGELOG_GITHUB_TOKEN"]

GitHubChangelogGenerator::RakeTask.new :changelog do |config|
  config.user = 'adrijshikhar'
  config.project = 'darkdev'
  config.token = TOKEN
end
