task :planet do
  sh "curl -L -o src/planet-latest.osm.pbf -C - https://planet.openstreetmap.org/pbf/planet-latest.osm.pbf"
end

task :extract do
  sh "osmium extract --polygon area/area.geojson --output a.pbf src/planet-latest.osm.pbf"
end
