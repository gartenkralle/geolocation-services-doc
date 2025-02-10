# geolocation-services-doc

## Design

### Component diagram

<br>

![Class diagram](_images/architecture-component-diagram.drawio.svg)

### Data flow diagram

<br>

![Class diagram](_images/architecture-data-flow.drawio.svg)

### Data format

<br>

![Class diagram](_images/architecture-data-format.drawio.svg)

<br>
<br>

![Class diagram](_images/architecture-quad-tree.drawio.svg)

<br>

### Front end

<br>

![Class diagram](_images/architecture-front-end.drawio.svg)

<br>

### Grid sizes

32 x 32<br>
64 x 64<br>
128 x128<br>
256 x 256<br>
512 x 512<br>
1024 x 1024<br>
2048 x 2048<br>
4096 x 4096<br>
8192 x 8192<br>
16384 x 16384<br>
32768 x 32768<br>
65536 x 65536

<br>

### Hardware

- AMD EPYC™ 9634
- 8 GB DDR5 RAM (ECC)
- 4 dedicated cores
- 256 GB NVMe SSD

### Costs

- Server (1x 10 EUR/month)
- Domain (4x 2 EUR/month)

<br>

### Server Tools

- dotnet
- mariadb-server
- rsync
- htop
- certbot
- postfix
- ssh
- scp
- tar
- systemd

<br>

### Dependencies

- Yarp.ReverseProxy
- Dapper
- MySqlConnector
- IP2Location.IPGeolocation
- Net.Codecrete.QrCodeGenerator
- Newtonsoft.Json
- Stripe
- MimeKit

<br>

## Progressive Web Apps

[https://www.nextpicnic.org](https://www.nextpicnic.org)  
[https://www.hofladenfinder.org](https://www.hofladenfinder.org)  
[https://www.nextparkinglot.org](https://www.nextparkinglot.org)

## Play Store

https://play.google.com/store/apps/details?id=org.nextpicnic2.www.twa

https://play.google.com/store/apps/details?id=org.hofladenfinder.www.twa

## Apple Store

https://apps.apple.com/app/next-picnic/id6443399146

https://apps.apple.com/app/hofladen-finder/id6502307062

## Windows Store

[https://apps.microsoft.com/store/detail/next-picnic/9N9CN0NJD073](https://apps.microsoft.com/store/detail/next-picnic/9N9CN0NJD073)

## Software as a Service

[https://www.geolocationservices.org](https://www.geolocationservices.org)

## Nuget packages

[https://www.nuget.org/profiles/GeolocationServices](https://www.nuget.org/profiles/GeolocationServices)

## Npm packages

[https://www.npmjs.com/~geolocation-services](https://www.npmjs.com/~geolocation-services)

## Rapid API

[https://rapidapi.com/organization/GeolocationServices](https://rapidapi.com/organization/GeolocationServices)
