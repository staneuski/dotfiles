tap "homebrew/bundle"

def brew_if(condition, *packages)
  packages.each { |pkg| brew pkg if condition }
end

brew_if OS.linux?,
  "entr",
  "gcc",
  "git-lfs",
  "numpy",
  "openssl@3",
  "pigz",
  "python@3.13",
  "rclone",
  "virtualenv"
