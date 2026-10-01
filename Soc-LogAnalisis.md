# SOC Log Analysis

## Objective
Practice analyzing Linux login logs using basic Linux commands.

## Sample Log

Login failed from 192.168.1.10
Login failed from 192.168.1.10
Login successful from 192.168.1.20

## Commands Used

### Search failed logins
grep "failed" login.log

### Count failed logins
grep -c "failed" login.log

### View latest log entries
tail login.log

### Sort log entries
sort login.log

## Security Observation

Two failed login attempts were recorded from the same IP address:
192.168.1.10

Repeated failed login attempts can be investigated as a possible
security event.

## Learning Outcome

I learned how Linux commands can be used to search and analyze
security-related log data.

## conclusion
I learned how to analyze authentication logs using Linux commands.
I participated identifying failed login attempts,finding up addresses,
and counting repeated login attempts.
This practice helped mi understand the basic process of security log analysis used in soc environments
