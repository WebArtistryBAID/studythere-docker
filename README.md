# StudyThere Docker

This is the Docker Compose configuration for StudyThere.

## Get Started

The Docker Compose configuration is intended to be run in production. For development, please check [WebArtistryBAID](https://github.com/WebArtistryBAID)/[**studythere-backend**](https://github.com/WebArtistryBAID/studythere-backend) and [WebArtistryBAID](https://github.com/WebArtistryBAID)/[**studythere-frontend**](https://github.com/WebArtistryBAID/studythere-frontend).

* Clone this repository.
* Run `git submodule update --init --recursive`.
* Move `.env.example` to `.env` and add your database credentials, JWT secret key, public hosting base URL, and authorization secrets accordingly.
* In the `frontend` directory, copy `.env.example` to `.env`. You should not change the contents of `.env` within the `frontend` directory.
* Run `docker-compose up -d`.
* You're ready to start!

## Contribution

To contribute, simply open a pull request.

## License

```
    StudyThere is a tool for students to find empty rooms.
    Copyright (C) 2024  Team WebArtistry

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

