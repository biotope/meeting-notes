# Agenda

1. Roadmap Update
2. Resource Loader
3. Node versions in travis
4. Availability
5. Biotope Element Bug

## Roadmap update
 - Documentation is beeing enhanced
 - Design for website still is not moving further ( => we reach out to other designers)
 - Quality gate: Biggest bug fixing still not working
 - Build vNext: Ready for projects. Being already used.
 - Grid: We see no real usecase for it
 
## Resource Loader
 - No events being fired 'resourcesReady'
 - @sheepfromheaven is investigating
 - resource-loader is "just a tool"
 - no need to use it in every project
 
## Node versions in travis
 - Proposal from @jurekbarth : only unse the latests LTS version of node in travis
 - at least in boilerplate (Visual regression testing)
 - we agree
 - @jurekbarth will update the travis files

## Availability
 - we get approached often (good! 👍)
 - @sheepfromheaven will be on parental leave
 - we still want to stay active
 - how will we handle this?
 - @tiagomapmarques will not be available
 - @jurekbarth will reserve more time for support
 - we will adress @timomayer about it

## Biotope Element Bugs
 - @biotope/element Component.register() does currently replace the tag
 - this leads to loosing of the reference of that component
 - removing the lines there seem to bring up an error in the build vNext
 - @sheepfromheaven will share compiled code with @tiagomapmarques
 
