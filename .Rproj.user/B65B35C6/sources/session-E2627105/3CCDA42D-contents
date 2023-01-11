# Created by use_targets().
# Follow the comments below to fill in this target script.
# Then follow the manual to check and run the pipeline:
#   https://books.ropensci.org/targets/walkthrough.html#inspect-the-pipeline # nolint

# Load packages required to define the pipeline:
library(targets)

# Set target options:
tar_option_set(
  packages = c("config")
)

# Read configs
env_name <- config::get("name")

# Replace the target list below with your own:
list(
  tar_target(
    name = my_env_name,
    command = env_name
  )
)
