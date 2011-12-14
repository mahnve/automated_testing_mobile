<!SLIDE center>

# Different Kind of Tests

![tests](test_quadrant.svg)

<!SLIDE center>

# What We Are Used To

![Web Test Eco System](web_ecosystem.svg)

. High Maturity

<!SLIDE bullets>

# What We Have In Mobile

* Basically where we where with Java web testing in 2001
* Slow
* Relies on unpublished API:s


<!SLIDE bullets>

# iOS Tools

* OCUnit
* Cedar
* KIF
* Runs in simulator


<!SLIDE >

# Android Tools

* Robotium - runs in Emulator
* Robolectric - runs in VM

<!SLIDE bullets>

# The Monkey

* Part of Android
* Clicks pseudo-randomly
* Easy to use

<!SLIDE commandline>

$ adb shell monkey [options] <event-count>

<!SLIDE bullets>

# What We've Done

* Gave up on existing tools
* Broke out logic into separate classes
* No integration tests
* Will look to RoboGuice

<!SLIDE bullets>

# Web Applications

* Runs in the browser
* Testable using standard webtools
* Can be run throught Selenium on both iOS and Android
