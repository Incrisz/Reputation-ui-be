# BizVisibility AI - Admin Documentation

Welcome to the BizVisibility AI Admin Panel! This document explains all the administrative features and capabilities available to administrators.

## 📋 Table of Contents

1. [Getting Started](#getting-started)
2. [Dashboard](#dashboard)
3. [Users & Businesses Management](#users--businesses-management)
4. [Plans Management](#plans-management)
5. [API Keys Configuration](#api-keys-configuration)
6. [Audits Management](#audits-management)
7. [Audit History](#audit-history)
8. [Profile Settings](#profile-settings)
9. [Administrative Features](#administrative-features)

---

## Getting Started

### Admin Access
- **Authentication**: Secure authentication with encrypted sessions
- **Permissions**: Admin users have full access to all administrative functions

### Navigation
The admin panel features a consistent navigation structure:
- **Header**: Contains logo, dark mode toggle, and profile menu
- **Sidebar**: Quick navigation to all major admin sections
- **Main Content**: Displays the current section's features and data

---

## Dashboard

### Admin Dashboard
- **Purpose**: Overview of platform metrics and system status
- **Key Features**:
  - **Key Metrics**:
    - Total active users
    - Total businesses tracked
    - Total audits completed this month
    - System uptime percentage
    - Revenue metrics (if applicable)
  - **User Statistics**:
    - New users this month
    - Active users
    - Plan distribution
    - Churn rate
  - **Activity Feed**:
    - Recent user signups
    - Recent audits completed
    - Recent plan upgrades
    - System alerts
  - **Health Indicators**:
    - API status
    - Database status
    - Cache status
    - Job queue status
  - **Quick Actions**:
    - View top users
    - View top businesses
    - Manage users
    - View recent audits

**What You Can Do**:
- Monitor overall platform health
- View key performance indicators
- Track user growth and engagement
- Monitor system status in real-time
- Access quick actions for common tasks
- View trends and patterns
- Identify potential issues

---

## Users & Businesses Management

### Users List Page
- **Purpose**: Manage all user accounts and their associated businesses
- **Key Features**:
  - **User Table**:
    - Search users by name or email
    - Filter by subscription plan
    - Filter by status (active/inactive)
    - Sort by various columns
    - Pagination for large datasets
  - **User Information**:
    - User ID
    - Name
    - Email address
    - Phone number
    - Subscription plan
    - Account status
    - Registration date
    - Last login date
  - **User Actions**:
    - View user details
    - Edit user information
    - Manage user subscription
    - Deactivate/Activate user
    - Send messages to user
    - View user activity log
    - Delete user account (with confirmation)
  - **Bulk Actions**:
    - Select multiple users
    - Bulk status changes
    - Bulk plan upgrades
    - Bulk messaging

**What You Can Do**:
- View all registered users
- Search and filter users
- View detailed user information
- Edit user profiles and information
- Manage user subscriptions and plans
- Send communications to users
- Deactivate or reactivate accounts
- View user activity and audit history
- Monitor user engagement

### User Details Page
- **Purpose**: In-depth management of individual user accounts
- **Key Features**:
  - **User Profile**:
    - Name, email, phone
    - Registration date
    - Account status
    - Plan information
    - Payment status
  - **Businesses**:
    - List of associated businesses
    - Business details
    - Audit count per business
    - Business status
  - **Subscription Details**:
    - Current plan
    - Plan start/end dates
    - Billing information
    - Payment history
    - Upgrade/downgrade history
  - **Activity Log**:
    - All user activities
    - Audit history
    - Login history
    - Settings changes
  - **Administrative Actions**:
    - Edit user information
    - Change subscription plan
    - Refund/credit management
    - Force password reset
    - Send notifications
    - View API usage
    - Manage permissions

**What You Can Do**:
- View comprehensive user information
- Access all user business profiles
- Review subscription and billing details
- Track user activity and audits
- Make account changes
- Manage user permissions
- Send direct messages
- View user's API access and usage
- Generate reports for specific users

---

## Plans Management

### Plans Management Page
- **Purpose**: Configure and manage subscription plans
- **Key Features**:
  - **Plans List**:
    - All available subscription plans
    - View/Edit/Delete functionality
    - Search and filter capabilities
    - Sort by price or features
  - **Plan Details**:
    - Plan name
    - Description
    - Monthly price
    - Annual price
    - Discount percentage (if annual)
    - Status (active/inactive)
    - Number of subscribers
  - **Plan Features**:
    - Number of audits per month
    - Number of businesses allowed
    - API access
    - Priority support
    - Custom branding
    - Advanced analytics
    - Data retention period
    - Export capabilities
  - **Add New Plan**:
    - Create custom plans
    - Set pricing
    - Define features
    - Configure limits
    - Set availability
  - **Edit Plan**:
    - Modify plan details
    - Update pricing
    - Add/remove features
    - Change availability
    - Grandfathering rules
  - **Delete Plan**:
    - Archive plans
    - Handle existing subscribers
    - Migration options

**What You Can Do**:
- View all subscription plans
- Create new custom plans
- Edit existing plans
- Update pricing and features
- Manage plan availability
- View subscriber counts per plan
- Define plan benefits and limits
- Set up promotional pricing
- Manage plan transitions
- Archive or deprecate plans

---

## API Keys Configuration

### API Keys Management Page
- **Purpose**: Manage and configure API credentials for external services
- **Key Features**:
  - **OpenAI Configuration**:
    - API Key management
    - Model selection
    - Base URL configuration
    - Test connectivity
  - **LLM Provider Selection**:
    - Switch between OpenAI and OpenRouter
    - Provider-specific settings
    - Cost and performance comparison
  - **OpenRouter Configuration**:
    - API Key
    - Model selection
    - Site URL and App Title
    - Rate limit configuration
  - **External APIs**:
    - **PageSpeed Insights**: Performance monitoring API
    - **Serper**: Search result analysis API
    - **Google Places**: Location data API
    - **Google Auth**: Authentication API
  - **Mail Configuration**:
    - Email service provider
    - SMTP settings
    - Security scheme (TLS, SSL)
    - Host and port configuration
    - Username and password
    - From address and name
  - **Key Management**:
    - Show/hide sensitive values
    - Validate API connections
    - Test endpoints
    - View key usage statistics
    - Rotation scheduling
    - Access logs

**What You Can Do**:
- Configure API credentials
- Choose LLM providers
- Set up email services
- Configure external integrations
- Toggle between providers
- Test API connections
- View configuration status
- Monitor API usage
- Manage key rotation
- Save configuration changes

---

## Audits Management

### Audits Page
- **Purpose**: Monitor and manage ongoing and completed audits
- **Key Features**:
  - **Audits List**:
    - All audits (active and completed)
    - Search by business name or user
    - Filter by status (pending, running, completed, failed)
    - Filter by audit type
    - Filter by date range
    - Sort capabilities
  - **Audit Information**:
    - Audit ID
    - Business name
    - User name
    - Audit type
    - Start date/time
    - Completion date/time
    - Overall score
    - Status
  - **Active Audits**:
    - Progress indicator
    - Time elapsed
    - Estimated completion time
    - Resources used
    - Cancel audit option
    - View logs
  - **Completed Audits**:
    - Final score
    - Result summary
    - Report download
    - Resend report option
    - Re-run audit option
    - View detailed results
  - **Failed Audits**:
    - Error message
    - Error logs
    - Retry option
    - Delete audit
    - Notify user option

**What You Can Do**:
- Monitor all audit activities
- View audit progress in real-time
- Cancel long-running audits
- Review audit results
- Download audit reports
- Retry failed audits
- View detailed audit logs
- Resend reports to users
- Analyze audit patterns
- Identify system issues

---

## Audit History

### Audit History Page
- **Purpose**: Review historical audit data and trends
- **Key Features**:
  - **Historical Data**:
    - All past audits
    - Chronological ordering
    - Complete audit details
    - Archive data access
  - **Analytics**:
    - Audit trends
    - Average scores over time
    - Most common findings
    - Performance metrics
    - Usage patterns
  - **Reporting**:
    - Generate trend reports
    - Export data
    - Custom date ranges
    - Filter by user/business
    - Comparison tools
  - **Insights**:
    - Top performers
    - Bottom performers
    - Industry averages
    - Improvement trends
    - Platform improvements

**What You Can Do**:
- Review historical audit data
- Generate trend analysis
- Export audit history
- Identify patterns and trends
- Compare performance over time
- Create custom reports
- Analyze platform usage
- Benchmark against industry standards

---

## Profile Settings

### Admin Profile Settings
- **Purpose**: Manage admin account and preferences
- **Key Features**:
  - **Account Information**:
    - Admin name
    - Email address
    - Phone number
    - Admin role/permissions
    - Account status
    - Last activity
  - **Security**:
    - Change password
    - Two-factor authentication (2FA)
    - Active sessions
    - Login history
    - API keys for admin actions
  - **Notifications**:
    - Alert preferences
    - Email notifications
    - System alerts
    - Audit failure alerts
    - Security alerts
    - Budget alerts
  - **System Preferences**:
    - Theme (light/dark)
    - Language
    - Timezone
    - Date format
    - Default views
  - **Audit Log**:
    - View all admin actions
    - Track changes made
    - Review configurations
    - Security audit trail

**What You Can Do**:
- Update admin information
- Change admin password
- Enable/disable 2FA
- Configure notification preferences
- View security logs
- Manage admin sessions
- Update system preferences
- Review all administrative actions

---

## Administrative Features

### System Management
- **Database Management**: Monitor database size and performance
- **Cache Management**: Clear and manage application cache
- **Job Queue**: Monitor background jobs and task scheduling
- **Logs**: View system and application logs
- **Error Tracking**: Monitor and track system errors
- **Performance Monitoring**: Track system performance metrics

### Reporting & Analytics
- **User Reports**: Generate user engagement reports
- **Financial Reports**: Track revenue and billing
- **Audit Reports**: Analyze audit statistics
- **System Reports**: Monitor system health
- **Custom Reports**: Create custom report queries
- **Export Options**: Export reports in various formats (PDF, CSV, Excel)

### Communication
- **User Messaging**: Send messages to users
- **Bulk Communications**: Send messages to groups
- **Announcement System**: Post platform announcements
- **Email Campaigns**: Run targeted email campaigns
- **In-app Notifications**: Send in-app notifications

### Integration Management
- **API Management**: Monitor API usage
- **Webhook Configuration**: Set up and manage webhooks
- **Third-party Integrations**: Manage external service connections
- **OAuth Configuration**: Manage authentication providers
- **Custom Integration**: Set up custom integrations

---

## Admin Levels & Permissions

### Super Admin
- Full access to all features
- User and business management
- Plan management
- API configuration
- System settings
- Financial management
- Audit logs access
- Ability to create other admins

### Platform Admin
- User and business management
- Audit management
- Plan management (limited)
- Report generation
- User communications
- Cannot modify system settings
- Cannot access API keys

### Support Admin
- View user information
- Respond to support tickets
- Generate basic reports
- Cannot modify user data
- Cannot access financial information
- Cannot modify plans

---

## Best Practices

1. **Regular Monitoring**: Check dashboard daily for system health
2. **User Management**: Regularly review inactive users
3. **Plan Management**: Update plans based on user feedback
4. **API Keys**: Rotate API keys periodically for security
5. **Audit Monitoring**: Monitor for failed audits
6. **Backup**: Regularly backup important data
7. **Security**: Keep admin credentials secure
8. **Logging**: Maintain audit logs for compliance
9. **Documentation**: Document all configuration changes
10. **Communication**: Keep users informed of updates

---

## FAQ

**Q: How do I reset a user's password?**
A: Go to Users Management, select the user, and use "Force Password Reset" option.

**Q: Can I modify existing plans?**
A: Yes, but changes only apply to new subscribers. Existing subscribers keep grandfathered pricing.

**Q: How often should I check the audit logs?**
A: We recommend checking logs at least weekly, or daily during high-usage periods.

**Q: What should I do if an API key is compromised?**
A: Immediately rotate the key in API Keys configuration and update all services using it.

**Q: Can I export user data?**
A: Yes, use the export function in Users management. For bulk exports, use Reports section.

---

## Troubleshooting

### Common Issues

**Issue**: API connection failing
- **Solution**: Verify API keys are correct and not expired. Check network connectivity.

**Issue**: Audits stuck in progress
- **Solution**: Check system logs. Cancel and retry. Contact support if persists.

**Issue**: Dashboard loading slowly
- **Solution**: Clear cache. Check database performance. Review system resources.

**Issue**: User locked out
- **Solution**: Use "Reset Password" or "Unlock Account" from user details page.

---

## Support

For admin support:
- **Admin Support Email**: admin-support@bizvisibility.ai
- **Internal Documentation**: https://docs.bizvisibility.ai/admin
- **Slack Channel**: #admin-support
- **Status Page**: https://status.bizvisibility.ai

---

## Security & Compliance

### Security Practices
- Always use HTTPS for admin panel access
- Enable two-factor authentication
- Regularly rotate API keys
- Monitor access logs
- Use strong passwords
- Logout after each session

### Compliance
- GDPR compliant user data handling
- SOC 2 certified processes
- Regular security audits
- Data encryption in transit and at rest
- Comprehensive audit logging

---

**Last Updated**: December 20, 2025
**Version**: 1.0
**Admin Panel Version**: 2.0.0
