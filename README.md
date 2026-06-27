## NextJS API---> Request Method

### app/api/request-method
```bash
import { NextRequest, NextResponse } from "next/server";


export async function GET(request:NextRequest) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is GET request"},
        {status: 200}
    )
}

export async function POST(request:NextRequest) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is POST request"},
        {status: 200}
    )
}

export async function PUT(request:NextRequest) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is PUT request"},
        {status: 200}
    )
}

export async function PATCH(request:NextRequest) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is PATCH request"},
        {status: 200}
    )
}

export async function DELETE(request:NextRequest) {
    
    return NextResponse.json(
        {status: "Success response", message: "This is DELETE request"},
        {status: 200}
    )
}
```
---
