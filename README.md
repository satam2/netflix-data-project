# netflix-data-project

in your IDE:</br>
add upstream branch: `git remote add upstream https://github.com/CS133-DataVisualization/CS133_Fa26_datafile.git` </br>
set origin: `git remote set-url origin https://github.com/satam2/news-popularity-data-project.git`

you know it works if you do `git remote -v` and the following appears:

`origin    https://github.com/satam2/news-popularity-data-project.git (fetch)` </br>
`origin    https://github.com/satam2/news-popularity-data-project.git (push)` </br>
`upstream  https://github.com/CS133-DataVisualization/CS133_Fa26_datafile.git (fetch)` </br>
`upstream  https://github.com/CS133-DataVisualization/CS133_Fa26_datafile.git (push)` </br>

to pull updates from original repo: `git sync-upstream` </br>
otherwise: `git pull origin main`
