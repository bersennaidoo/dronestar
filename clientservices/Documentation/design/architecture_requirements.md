# Architecture Nonfunctional-Requirements

Architecture design describes the systems hardware, software and networking environment with respect to

1. Operational requirements

2. Performance requirements

3. Security requirements

4. Cultural and Political requirements

Deliverables architecture design, hardware and software specification/requirements which expands
the logical process model into physical process models with above requirements satisfied thus producing
an architecture design for the information system.

## Operational Requirements

#### Technical Environment

    1. The system will work over the Web with any browser
    2. Nonregistered customers using mobile devices will access the system using the mobile device browser
    3. Registered clients and pilots using mobile devices will access a rich Internet application from the
       mobile device browser 

#### System Integration

    4. The informational portion of the system will read content from the drone database in the Sales
       system. No write access is allowed.
    5. The portion of the system for registered clients and pilots will read and write to the client, pilot,
       flight request, and flight bid datastores
    6. Data from completed drone flights must be uploaded from anywhere into the DroneStar private
       cloud storage
    7. Clients can download completed drone video from the DroneStar cloud storage
    8. Clients can download completed data analyses from the DroneStar cloud storage

#### Portability

    9. iOS and Android devices are supported

#### Maintainability

    10. The system will need to remain current with evolving Web standards, especially those pertaining
        to Web video formats.

## Performance Requirements

#### Speed

    1. Response times must be less than 7 seconds
    2. Upload and download speeds must be maintained above the industry norm

#### Capacity

    3. There will be a maximum of 100 simultaneous users at peak use times
    4. The system will support streaming video to up to 50 simultaneous users

#### Availability

    5. The system should be available 24/7

#### Reliability

    6. The system shall have 99% uptime performance

## Security Requirements

#### System Value

    1. The system has high strategic value and is essential to the functioning of the new Client Services
       business unit

#### Access Control/Authentication

    2. Registered clients and pilots will access their accounts with username and password

#### Encryption

    3. Client payment information must be transmitted securely 
    4. Drone data uploads and completed drone videos and data analyses must be transmitted securely

#### Virus Control

    5. All standard virus controls are mandated

## Cutural and Political Requirements

#### Multilingual

    1. No special multilingual requirements are expected

#### Customization

    2. Pilots will be provided customization options for the pilot dashboard

#### Unstated Norms

    3. No special unstated norms are expected

#### Legal

    4. No special legal requirements are expected
