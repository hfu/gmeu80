task :default do
  sh "gunzip RoadL.dbf.gz"
  sh "gunzip WatrcrsL.dbf.gz"
  sh "gunzip RailrdL.dbf.gz"
end
task :archive do
  sh "gzip -9 RoadL.dbf"
  sh "gzip -9 WatrcrsL.dbf"
  sh "gzip -9 RailrdL.dbf"
end
