# ULTIMATE Product CRUD App - **ProductHUBre** -
##  Functionalities: Product creation, retrieval, modification, filtering and deletion

![Corera](corera.png)

## Overview

This project implements a comprehensive CRUD (Create, Read, Update, Delete) application for managing products, built using React, EasyUI, and a REST API. The application offers features like filtering, pagination, and column customization within a user-friendly grid interface.

- **Complete CRUD Operations:** Create, read, update, and delete products.
- **Advanced Filtering:** Filter data based on multiple criteria.
- **Customizable Grid:** Adjust column widths to suit your preferences.
- **Pagination:** Easily navigate through large datasets.
- **REST API Integration:** Consumes a REST API for data management (no direct database connection).

## Live Demo:

Access the live demo at : [https://product-hu-bre.vercel.app/](https://product-hu-bre.vercel.app/)

## Technical Stack

**Frontend:** React, EasyUI

**Backend:** REST API (JSON-based) https://product-api-smoky.vercel.app/

You can access the API repository here https://github.com/fabinnerself/productAPI.gi

## Infrastructure:
OS: Ubuntu 20.04.6 LTS or 24.04.4 LTS, Windows 10 Pro 1803

**Node.js:** v20.15.0

**npm/npx:** 10.8.1

**React:** 18.3.1

**EasyUI:** 1.10.19

## Getting Started Instalation
  
1. Create React App:

```bash
    npm install -g create-react-app

    npm i axios

    create-react-app my-app

    cd my-app
 ```

2.  Install  EasyUI for React.

```bash
    npm install rc-easyui --save
 ```

3. Import CSS.

```react

    @import '~rc-easyui/dist/themes/default/easyui.css';

    @import '~rc-easyui/dist/themes/icon.css';

    @import '~rc-easyui/dist/themes/react.css';
```

4. Use EasyUI Components:

```react
    import { DataGrid, GridColumn } from 'rc-easyui';
```

5. Run the App:

```bash
    npm   start
```

Additional Notes:

- The corera.png screenshot provides a visual representation of the application's interface.

- The REST API is used to fetch and manipulate product data without a direct database connection.

- The grid component offers features like filtering, pagination, and column resizing for enhanced user experience.

- The rc-easyui library is used to build the interactive grid interface for product data.  For more details on this library, you can refer to the official documentation: https://www.jeasyui.com/download/rc.p

### Useful Commands:

System Information:

```Bash

lsb_release -a && uname -r

node -v && nvm -v && npm -v && npx -v
```

Copyright:
(C) 2024 Favian Medina Gemio

 