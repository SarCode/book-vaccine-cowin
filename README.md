<p align="left"> <img src="https://komarev.com/ghpvc/?username=sarcode&label=Profile%20views&color=0e75b6&style=flat" alt="sarcode" /> </p>

[![LinkedIn][linkedin-shield]][linkedin-url]

# Automated Covid Vaccine Booking (Archived)

**This project is archived and no longer functional.** It was built during India's
2021 COVID-19 vaccination drive to help automatically find and book vaccine slots
on CoWIN (the Indian government's vaccination portal) by pincode or district. The
vaccination drive that this tool targeted has since ended, and the CoWIN API
endpoints it relied on have been decommissioned. Downloading and running the
executable below will not book any vaccine slots today - it is kept here purely
for historical reference.

## What's in this repository

- `covid-vaccine-slot-booking.exe` - a precompiled Windows executable (built with
  PyInstaller). The original Python source was never published to this repository -
  only the compiled binary was uploaded, so it cannot be audited or modified.
  Inspection of the binary shows it bundles Python's `requests`, `urllib3`, and
  `certifi` libraries, consistent with a script that polled the CoWIN HTTP API.

Because the source was never committed, there is no build process, dependency
list, or code in this repo to maintain - the executable is the only artifact.

**A general caution:** running an unsigned executable downloaded from a personal
GitHub repository always carries some risk, regardless of the original intent.
Treat this binary as a historical curiosity, not as software to run.

## Credit

Based on a program by [Pallupz](https://github.com/pallupz).

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sarthak-agarwal-dell/
