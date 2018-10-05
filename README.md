# Auto Publish Email

## Synopsis

Summier overzicht:

- Purpose
- Some Text...
- ...


## Technical

|Role              | Handle / username|
| -------------    |--------------| 
|Principal/Owner   | @ | 
|Wing(wo)man       | @ |
|Operator          | @ |

**Code Review:**

## Functional

## Server

|               | QAS           | PRD      |
| ------------- |:-------------:| :-----:  |
| **host**      | fill in       | fill in  |

## Stack

#### Backend


### Frontend

## Logging and monitoring

#### Backend

#### Frontend

## Deployment/Installation

#### Prerequisites

#### Backend

#### Frontend

## Usage

#### Examples

### Troubleshooting

## Process Flow

This application will be triggered by a message on RabbitMQ.

#### Flow

The application will:
- Get all organisations
- For every organisation
    - Get statistics about their archive
    - Get users from this organisation
    - For every user
        - Use glue (Campaign Monitor) to send an email to the user
- Send a notification to Slack with the emails sent per organisation

#### Diagram

