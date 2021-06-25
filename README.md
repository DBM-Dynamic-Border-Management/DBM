# DBM
DBM is the new way of organizing all of your project as a team. Using chat solution as Mattermost, find back every information, data, links, file you need in less than two clicks. A well made information organisation is a well made management.

 
DBM propose a window on the right border of your communication app (atm only on Mattermost) that allows you to insert and organize your most important links in a same place. Whether its your figma project or your next big excel online, give you the shortcut you need. It prevents you from losing time searching for every ressource and it adapts within every other project you create.

![CANAL_DE_DISCUSSION_AUTRE_GROUPE](https://user-images.githubusercontent.com/44975619/123269068-e7c28a00-d4fe-11eb-83bf-65e8d43beceb.jpg)


## Setup

You will need to have the api in local, so check this repo : https://github.com/DBM-Dynamic-Border-Management/dbm-api
## Installation

- docker run --name mattermost-preview -d --publish 8065:8065 --add-host dockerhost:127.0.0.1 mattermost/mattermost-preview


- git clone https://github.com/DBM-Dynamic-Border-Management/DBM

- make

- go to http://localhost:8065/admin_console/plugins/plugin_management and upload the targz generate by the make command

## Usage example

A few motivating and useful examples of how your product can be used. Spice this up with code blocks and potentially more screenshots.

_For more examples and usage, please refer to the [Wiki][wiki]._
## Versioning
# V 0.1

The objectives of this mvp is to provide the following functionalities:

- Creation of the api in a simple and modifiable version.
- Modification of the mattermost frontend with the main objective to integrate a fully cutstom sidebar.
- Make the new frontend work with the api.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bee5d705-68c9-4409-b5be-f1fc9109f9ab/Untitled.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/bee5d705-68c9-4409-b5be-f1fc9109f9ab/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210625%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210625T090608Z&X-Amz-Expires=86400&X-Amz-Signature=06932564ac2dbe5b544cb2e4483c159132e19648d4a4a280f59e97b060b1975c&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aeee489d-3ea7-4365-a917-382248781655/Untitled.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/aeee489d-3ea7-4365-a917-382248781655/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210625%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210625T090649Z&X-Amz-Expires=86400&X-Amz-Signature=eb76a73d34a7ffa7372fd290869aa4716846ce008e5941f8181f7d86c58f8b3b&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

# V 0.2

The objectives of this v1 is to provide the following features:

- Add the ability to add files in addition to links.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/89f8f430-a0a7-45f1-9995-5155e8606e5a/Untitled.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/89f8f430-a0a7-45f1-9995-5155e8606e5a/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210625%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210625T090819Z&X-Amz-Expires=86400&X-Amz-Signature=b490727ae96c392d5f6307c849712faa6cdcaf6942c84f4a5a20a2cfc26ea64c&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

# V 1.0

The objectives of this v2 is to provide the following features:

- Add a command per channel to create automatically all the collaborative tools and enter the links in the sidebar.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b80c80ee-b03f-4f0f-808b-7ec594401a21/Untitled.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/b80c80ee-b03f-4f0f-808b-7ec594401a21/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210625%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210625T090823Z&X-Amz-Expires=86400&X-Amz-Signature=61ec8ccf2d50741f7ede537851dfdd14c553099d5a0b17a60c242074623cdd47&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

# V 2.0

The objectives of this v3 is to provide the following features:

- Use mattermost for team meetings and use a collaborative text tool on this call and automatically generate the rendering file at the end of the meeting.
- Create notification before a meeting and display the last review.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4a570553-6c45-49c1-8fb7-40016077e8dc/Untitled.png](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/4a570553-6c45-49c1-8fb7-40016077e8dc/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210625%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210625T090826Z&X-Amz-Expires=86400&X-Amz-Signature=bdc593436b30892be9d917db24fe06eaea8b04dadc7d2c48501e0a38e96e1cc2&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22)

## Meta

Your Name – [@DBM_Solution](https://twitter.com/DBMgithub) – DBM-github@gmail.com

Distributed under the Apache 2.0 license. See `LICENSE` for more.
## Contributing

1. Fork this repo
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request