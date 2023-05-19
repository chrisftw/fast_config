There are 4 test files. You can run them all at once:

        bundle exec ruby test/all.rb 

Or run each independently:

        bundle exec ruby test/fast_config_test.rb

        bundle exec ruby test/fast_config_config_dir_setting_test.rb 

        bundle exec ruby test/fast_config_yaml_aliases.rb

        FAST_CONFIG_DIR="test/test_config" bundle exec ruby test/fast_config_with_env_test.rb
