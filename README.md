gem install ruboto
gem install jruby-jars
ruboto gen app --package com.test.me --name Test --target android-14 --with-jruby
rake install
