# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-16 12:45:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 138663.9 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776189
telemt_connections_bad_total 54217
telemt_handshake_timeouts_total 24899
telemt_upstream_connect_attempt_total 31980
telemt_upstream_connect_success_total 31824
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 31980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39165
telemt_me_reconnect_success_total 24932
telemt_me_reader_eof_total 26895
telemt_me_idle_close_by_peer_total 26895
telemt_me_route_drop_no_conn_total 613599
telemt_me_route_drop_channel_closed_total 97
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 711991
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3396
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2122
telemt_desync_frames_bucket_total{bucket="1_2"} 713
telemt_desync_frames_bucket_total{bucket="3_10"} 1421
telemt_desync_frames_bucket_total{bucket="gt_10"} 1262
telemt_pool_swap_total 125
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25648
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24897
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 716
telemt_user_connections_total{user="hello"} 648469
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 13558167208 (12.63 GB)
telemt_user_octets_to_client{user="hello"} 373809202548 (348.14 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 138672.3 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323995
telemt_connections_bad_total 4675
telemt_handshake_timeouts_total 20840
telemt_upstream_connect_attempt_total 36988
telemt_upstream_connect_success_total 36881
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 853
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 43307
telemt_me_reconnect_success_total 29363
telemt_me_reader_eof_total 31536
telemt_me_idle_close_by_peer_total 31535
telemt_me_route_drop_no_conn_total 153117
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286586
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 230
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30218
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29347
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 855
telemt_user_connections_total{user="hello"} 286267
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 5798055713 (5.40 GB)
telemt_user_octets_to_client{user="hello"} 140922953368 (131.24 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 138663.8 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310725
telemt_connections_bad_total 5984
telemt_handshake_timeouts_total 8971
telemt_upstream_connect_attempt_total 38240
telemt_upstream_connect_success_total 38232
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38702
telemt_me_reconnect_success_total 31257
telemt_me_reader_eof_total 33561
telemt_me_idle_close_by_peer_total 33560
telemt_me_route_drop_no_conn_total 105560
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254556
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 31810
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31249
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 553
telemt_user_connections_total{user="hello"} 254151
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 18980212405 (17.68 GB)
telemt_user_octets_to_client{user="hello"} 131823294712 (122.77 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 138663.3 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472656
telemt_connections_bad_total 3074
telemt_handshake_timeouts_total 5800
telemt_upstream_connect_attempt_total 32088
telemt_upstream_connect_success_total 32040
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 32087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 30132
telemt_me_reconnect_success_total 25123
telemt_me_reader_eof_total 26890
telemt_me_idle_close_by_peer_total 26889
telemt_me_route_drop_no_conn_total 159022
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 435031
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1566
telemt_desync_full_logged_total 524
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 577
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 25616
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 25112
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 434855
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 6671432998 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 164571418300 (153.27 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 113734.7 (31h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295619
telemt_connections_bad_total 54831
telemt_handshake_timeouts_total 5224
telemt_upstream_connect_attempt_total 32369
telemt_upstream_connect_success_total 32190
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 32369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121960
telemt_me_reconnect_success_total 26343
telemt_me_reader_eof_total 27980
telemt_me_idle_close_by_peer_total 27980
telemt_me_route_drop_no_conn_total 87854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226574
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 717
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 26613
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26239
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 226154
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 2932385153 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 104159895111 (97.01 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 138663.5 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1005625
telemt_connections_bad_total 77954
telemt_handshake_timeouts_total 12747
telemt_upstream_connect_attempt_total 29385
telemt_upstream_connect_success_total 29231
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 29385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 25944
telemt_me_reconnect_success_total 22293
telemt_me_reader_eof_total 23797
telemt_me_idle_close_by_peer_total 23796
telemt_me_route_drop_no_conn_total 718509
telemt_me_route_drop_channel_closed_total 137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976590
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22680
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22266
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 835173
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 17823471224 (16.60 GB)
telemt_user_octets_to_client{user="hello"} 478370592420 (445.52 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 111
```