# Server Side Events #

Parent repository to run an API and UI repositories for testing server side events

Pull the repository with the submodules, run the dotnet API, then run multiple angular UIs using different ports and configurations to represent different users. There are 3 configuration options 

- development - (default) this lists all events
- user - this lists only events with a value > 249
- admin - this lists only events with a value < 250
