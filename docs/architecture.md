# Architecture — Earth Elements Visibility Stack

This case study is documentation-only. There is no application runtime.

## Components

```text
┌─────────────────────────────────────────────────────────────┐
│                    Customer Discovery                        │
│  Google Search / Google Maps / “near me” queries             │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│              Google Business Profile (Verified)              │
│  • Correct category & description                            │
│  • Location / service area                                   │
│  • Photos, hours, contact                                    │
│  • Links to Instagram + Facebook                             │
└──────────────────────────┬──────────────────────────────────┘
                           │
           ┌───────────────┴───────────────┐
           ▼                               ▼
┌─────────────────────┐         ┌─────────────────────┐
│     Instagram       │         │      Facebook       │
│  @earth_elements369 │         │  Profile / Page     │
│  Visual proof + DM  │         │  Social proof + msg │
└─────────────────────┘         └─────────────────────┘
           │                               │
           └───────────────┬───────────────┘
                           ▼
                 Conversation → Booking / Sale
```

## Data Flow

1. User searches locally on Google.
2. Google Business Profile appears in Maps / local pack.
3. User opens profile → sees consistent branding and social links.
4. User continues to Instagram or Facebook for more proof or direct message.
5. Conversion happens in the messaging channel the customer prefers.

## Ownership

- Google Business Profile: owned and managed by Earth Elements.
- Instagram & Facebook: owned and managed by Earth Elements.
- This repository: public documentation of the setup process performed by MADS / SNTL 84.
