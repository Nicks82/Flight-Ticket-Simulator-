# Flight-Ticket-Simulator-
In this program I want to simulate selling flight tickets from Buffalo to Orlando.          There are three ticket agents responsible for selling tickets.           There are also three types of tickets an agent can sell, Main Cabin(153 seats), Extra Leg Room(18 seats),           First Class(16 seats).  To make this more realistic we wont be replicating three ticket agent functions (i.e copy and paste).           Instead, we declare one ticket agent function and call it passing a ticket agent ID#(1, 2 or 3).           In order to preserve realism we operate three ticket agents in parallel.  This means each agent can operate independantly,           they will not have to wait for the agent ahead of them to sell a ticket before they can start selling to the next customer.           Also, for realsim I generate a customers ticket choice randomly.           Once a ticket is sold each agent should keep track of the tickets that are remaining and the amount of tickets the agent           has sold and display this report to the screen. The total number of seats adds up to 187, so we decrement the total after each purhcase to keep track of what we have left.
