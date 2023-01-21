# Static-connection-between-PC-and-Router-MAC.
# this is command to make the connection between PC and Router Mac address Static to prevent Netcut tools against your PC.

# Open CMD
# write this command

netsh -c interface ipv4 add neighbors "NIC name" <Router ip> <Router MAC>

# NIC name --> your running network interface card name and if it contain spaces put the name between quotations

# you can save this in text file on desktop with .bat extension
netsh -c interface ipv4 add neighbors "NIC name" <Router ip> <Router MAC>
pause

pause --> used to freeze the cmd window to see if there is errors untill u press any key if not or solving the problem.
