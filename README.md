# Squadkin Base Module

**Copyright (c) 2025 Squadkin. All Rights Reserved.**

**PROPRIETARY SOFTWARE - DO NOT COPY OR DISTRIBUTE**

## Overview

Squadkin Base is a proprietary Magento 2 extension that provides core infrastructure and foundation functionality for all Squadkin modules. This module serves as the base layer for Squadkin extensions, specifically designed for integration with SquadexaAI - our exclusive AI-powered product generation platform.

This module is unique in the market and is the only authorized base module for Squadkin extensions.

## Main Functionalities

- **Base Infrastructure**: Provides core foundation for all Squadkin Magento 2 extensions
- **Admin Menu Integration**: Creates the main "Squadkin" menu item in Magento admin sidebar
- **Extension Foundation**: Serves as the base module for SquadexaAI and other Squadkin extensions

### Module Structure
- PSR-4 autoloading support
- Magento 2 coding standards compliance
- Proper module registration and configuration

## Installation

\* = in production please use the `--keep-generated` option

### Type 1: Manual Installation (Zip file)

1. Extract the module files to `app/code/Squadkin/Base`
2. Enable the module:
   ```bash
   php bin/magento module:enable Squadkin_Base
   ```
3. Apply database updates:
   ```bash
   php bin/magento setup:upgrade
   ```
4. Flush the cache:
   ```bash
   php bin/magento cache:flush
   ```

### Type 2: Composer Installation

1. Add the module to your composer repository (private repository recommended)
2. Install via Composer:
   ```bash
   composer require squadkin/module-base
   ```
3. Enable the module:
   ```bash
   php bin/magento module:enable Squadkin_Base
   ```
4. Apply database updates:
   ```bash
   php bin/magento setup:upgrade
   ```
5. Flush the cache:
   ```bash
   php bin/magento cache:flush
   ```

## Requirements

- **Magento Version**: 2.4.x or higher
- **PHP Version**: 8.0 or higher
- **Magento Backend Module**: Required

## Module Dependencies

- `Magento_Backend` - For admin menu functionality
- `Magento_Framework` - Core Magento framework


## License

This software is proprietary and confidential. All rights reserved.

**UNAUTHORIZED COPYING, REPRODUCTION, DISTRIBUTION, OR USE OF THIS SOFTWARE, VIA ANY MEDIUM, IS STRICTLY PROHIBITED AND MAY RESULT IN SEVERE CIVIL AND CRIMINAL PENALTIES.**

See `LICENSE.txt` for full license terms.

## Support

For licensing inquiries, technical support, or questions:

- **Company**: Squadkin Technologies Pvt. Ltd.
- **Email**: support@squadkin.com
- **Website**: https://www.squadkin.com/

## Copyright

© 2025 Squadkin. All rights reserved.

This software is protected by copyright law and international treaties. Unauthorized reproduction or distribution of this software, or any portion of it, may result in severe civil and criminal penalties, and will be prosecuted to the maximum extent possible under law.

## Version

Current Version: 1.0.0

## Changelog

### Version 1.0.0
- Initial release
- Admin menu integration
- Custom logo support
- Base infrastructure for Squadkin extensions
