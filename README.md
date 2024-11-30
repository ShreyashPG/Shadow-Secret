
# Shadow Secret 🔐  

**Shadow Secret** is a secure, encrypted text-sharing tool designed to ensure that your secrets remain confidential during conversations. With advanced encryption and customizable message expiration, it provides a reliable way to share sensitive information securely.

## Features ✨  

- **AES-256 Encryption**: Messages are encrypted using strong AES-256 encryption for top-level security.  
- **User-Provided Password Protection**: Users provide a password to encrypt and decrypt messages, ensuring only authorized access.  
- **Message Expiration**: Set expiration times for messages to auto-delete after a specified duration.  
- **Secure Storage**: Messages are stored securely using the **Crypto module** for encryption and an expiration mechanism for timely deletion.  

## Technologies Used 🛠️  

- **Next.js**: Fast and efficient server-side rendering and static site generation.  
- **TypeScript**: Ensures type safety and enhanced code quality.  
- **MongoDB**: Database for secure storage of encrypted messages.  
- **Prisma**: ORM for seamless database interaction.  
- **Crypto Module**: Implements AES-256 encryption for message security.  

## Getting Started 🚀  

### Prerequisites  

Ensure you have the following installed:  
- **Node.js**  
- **npm** or **yarn**  

### Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/ShreyashPG/Shadow-Secret.git 
   cd shadowsecret
   ```  

2. Install dependencies:  
   ```bash  
   npm install  
   # or  
   yarn install  
   ```  

3. Configure Environment Variables:  
   Create a `.env` file and add the following variables:  
   ```env  
   DATABASE_URL=<your-mongodb-connection-string>  
   NODE_ENV=development
   BASE_URL=http://localhost:3000
   ```  

4. Run the development server:  
   ```bash  
   npm run dev  
   # or  
   yarn dev  
   ```  

5. Access the app at [http://localhost:3000](http://localhost:3000).  

## Usage Instructions 📘  

1. Enter your message.  
2. Provide a password to encrypt the message.  
3. Set an expiration time (e.g., 10 minutes, 1 hour, 1 day).  
4. Share the generated link securely.  
5. The recipient enters the provided password to decrypt the message.  


---  

**Shadow Secret**: Share secrets, securely. 🔒  
