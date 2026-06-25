## NextJS API Request Method

### Request method
```bash
import { NextResponse } from "next/server";


export async function GET(request:Request) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is GET request"},
        {status: 200}
    )
}

export async function POST(request:Request) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is POST request"},
        {status: 200}
    )
}

export async function PUT(request:Request) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is PUT request"},
        {status: 200}
    )
}

export async function PATCH(request:Request) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is PATCH request"},
        {status: 200}
    )
}

export async function DELETE(request:Request) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is DELETE request"},
        {status: 200}
    )
}
```
---
