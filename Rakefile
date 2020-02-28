Rake::TaskManager.record_task_metadata = true
SAY = true

def say(t)
  sh "say #{t.full_comment}", verbose: false
end

desc "fitter, happier"
task :default do |t|
  say(t)
end
