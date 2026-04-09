l
Thelma -> .Net Backend Developer

**Five Patterns that Separate Tutorial From Production**
1. Stop Leaking Exceptions -> Global handling error
	***Benefits***
	- Catches unhandled Exceptions
	- RFC 7087 format, perse sable by any client
2. Stop Trusting Input -> Validation done right (FluentValidation - Automatic & Powerful)
3. Stop Returning Entities -> Result Pattern. DTOs + actual data (Returning entities = Data Breach). Use DTO + AutoMapper + Result Pattern
	***Benefits***
	- No sensitive data leaked
	- Control what clients see
	- Version responses (v1, v2)
	- Reduce payload size
4. Stop Breaking Clients -> API Versioning. A "Small" change breaks production
5. Stop Faking Security -> Auth & Authorization
	***Security Layers***
	 - Authentication - Who are you? (JWT)
	 - Authorization - What can you do? (Policies)
	 - Resource-level - Can you access this?
	 - Rate Limiting - How often? (Built in)