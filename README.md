markdown
# EAN Lookup

Welcome to the EAN Lookup MCP Server! This server provides a robust API that allows developers and businesses to access a comprehensive database containing over 430 million barcodes. The EAN Lookup service is ideal for applications in mobile apps, e-commerce platforms, and data warehouses, facilitating tasks such as updating product data, assisting with data entry, and integrating EAN codes into shopping uploads.

## Key Features

- **Query Products by Barcode**: Retrieve detailed product information using EAN or UPC barcodes.
- **Search by EAN Prefix**: Find products by searching with an EAN prefix, such as `0885909*`.
- **Keyword Search**: Discover products by searching with relevant keywords.
- **Flexible Response Formats**: Choose between XML and JSON for your API responses.

The EAN Lookup server supports a variety of use cases, including:

- **Product Data Updating**: Maintain up-to-date product information effortlessly.
- **Data Entry Assistance**: Streamline data entry processes with accurate product details.
- **Shopping Upload Integration**: Enhance your listings on platforms like Amazon or Google Shopping by adding EAN codes.

## Available Tools

The server provides the following tools to interact with its extensive database:

1. **Barcode Lookup**: 
   - Description: Lookup product information by entering a barcode.
   - Parameters:
     - `op`: Operation (String)
     - `ean`: Barcode to lookup (Number)
     - `format`: Output format, either JSON or XML (String, optional)

2. **Product Search**: 
   - Description: Search the barcode database using keywords.
   - Parameters:
     - `name`: Keywords to search for (String)
     - `op`: Operation (String)
     - `page`: Page through the output (Number, optional)
     - `format`: Output format, either JSON or XML (String, optional)

3. **Barcode Prefix Search**: 
   - Description: Search for barcodes that start with a specific prefix.
   - Parameters:
     - `prefix`: Barcode prefix (between 4 to 12 digits, Number)
     - `op`: Operation (String)
     - `page`: Page through the output (Number, optional)
     - `format`: Output format, either JSON or XML (String, optional)

4. **Verify Checksum**: 
   - Description: Verify the checksum of an EAN barcode.
   - Parameters:
     - `format`: Output format, either JSON or XML (String, optional)
     - `op`: Operation (String)
     - `ean`: Barcode to verify (Number)

## Conclusion

The EAN Lookup MCP Server is a powerful tool for anyone needing to access detailed product information quickly and reliably. Whether you're developing a mobile app, managing an e-commerce platform, or maintaining a data warehouse, this server offers the tools you need to integrate barcode data seamlessly into your projects. Explore its features today and see how it can enhance your operations.