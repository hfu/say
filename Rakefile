Rake::TaskManager.record_task_metadata = true
SAY = true

def say(t)
  sh "espeak -ven+f2 -k5 -s160 '#{t.full_comment}'", verbose: false if SAY
end

desc "fitter, happier"
task :default do |t|
  say(t)
end

desc "rake docker:run"
task :rake do |t|
  say(t)
end

desc "The United Nations Vector Tile Toolkit is a collection of Open Source Software to produce, host, style, and optimize basemap vector tiles, maintained under the United Nations Open GIS Initiative."
task :unvt do |t|
  say(t)
end

desc "
WE THE PEOPLES OF THE UNITED NATIONS DETERMINED
to save succeeding generations from the scourge of war, which twice in our lifetime has brought untold sorrow to mankind, and
to reaffirm faith in fundamental human rights, in the dignity and worth of the human person, in the equal rights of men and women and of nations large and small, and
to establish conditions under which justice and respect for the obligations arising from treaties and other sources of international law can be maintained, and
to promote social progress and better standards of life in larger freedom,
AND FOR THESE ENDS
to practice tolerance and live together in peace with one another as good neighbours, and
to unite our strength to maintain international peace and security, and
to ensure, by the acceptance of principles and the institution of methods, that armed force shall not be used, save in the common interest, and
to employ international machinery for the promotion of the economic and social advancement of all peoples,
HAVE RESOLVED TO COMBINE OUR EFFORTS TO ACCOMPLISH THESE AIMS
Accordingly, our respective Governments, through representatives assembled in the city of San Francisco, who have exhibited their full powers found to be in good and due form, have agreed to the present Charter of the United Nations and do hereby establish an international organization to be known as the United Nations."
task :charter do |t|
  say(t)
end
