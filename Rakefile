desc "Ejecutar rps en el servidor thin (puerto 9292)"
task :default do
  sh "rackup"
end

desc "Ejecutar el cliente con piedra"
task :rock do
  sh "ruby rps.rb ; curl -v 'http://localhost:9292/?eleccion=Piedra'"
end

desc "Ejecutar el cliente con papel"
task :paper do
  sh "ruby rps.rb ; curl -v 'http://localhost:9292/?eleccion=Papel'"
end

desc "Ejecutar el cliente con tijeras"
task :scissors do
  sh "ruby rps.rb ; curl -v 'http://localhost:9292/?eleccion=Tijeras'"
end
