require 'rake' # oh yeah!!

task :test do
  1.upto(100) do
    sleep(0.01)
    putc '.'
    $stdout.flush
  end
  exit 0
end

task :default => :test
