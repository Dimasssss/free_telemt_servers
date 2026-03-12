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

# Server Metrics 2026-03-12 13:34:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21656.3 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114470
telemt_connections_bad_total 546
telemt_handshake_timeouts_total 3853
telemt_upstream_connect_attempt_total 5245
telemt_upstream_connect_success_total 5221
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 243
telemt_me_reconnect_attempts_total 4125
telemt_me_reconnect_success_total 4099
telemt_me_reader_eof_total 4293
telemt_me_idle_close_by_peer_total 4292
telemt_me_route_drop_no_conn_total 32401
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101744
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 301
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4131
telemt_me_writer_restored_same_endpoint_total 4083
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 101708
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 1602626580 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 38803945088 (36.14 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21549.4 (5h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46546
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 6393
telemt_upstream_connect_success_total 6239
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 6393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3630
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 20983
telemt_me_reconnect_success_total 5154
telemt_me_reader_eof_total 5731
telemt_me_idle_close_by_peer_total 5731
telemt_me_route_drop_no_conn_total 20293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44417
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 5674
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5139
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 44415
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 544486692 (519.26 MB)
telemt_user_octets_to_client{user="hello"} 12311269876 (11.47 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21513.1 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62723
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 698
telemt_upstream_connect_attempt_total 5861
telemt_upstream_connect_success_total 5861
telemt_upstream_connect_attempts_per_request{bucket="1"} 5861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4782
telemt_me_reconnect_success_total 4746
telemt_me_reader_eof_total 5010
telemt_me_idle_close_by_peer_total 5010
telemt_me_route_drop_no_conn_total 22059
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59032
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4779
telemt_me_writer_restored_same_endpoint_total 4726
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 59015
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 1804359820 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 35183561156 (32.77 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21488.6 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81066
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 368
telemt_upstream_connect_attempt_total 5871
telemt_upstream_connect_success_total 5725
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 5871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 13728
telemt_me_reconnect_success_total 4620
telemt_me_reader_eof_total 5034
telemt_me_idle_close_by_peer_total 5034
telemt_me_route_drop_no_conn_total 29397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74265
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 223
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4958
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 4612
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 74171
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1234719212 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 33390566916 (31.10 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21458.1 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46737
telemt_connections_bad_total 4045
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 14249
telemt_upstream_connect_success_total 14000
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 14249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 27296
telemt_me_reconnect_success_total 3655
telemt_me_reader_eof_total 4390
telemt_me_idle_close_by_peer_total 4390
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31630
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4415
telemt_me_refill_failed_total 740
telemt_me_writer_restored_same_endpoint_total 3638
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 760
telemt_user_connections_total{user="hello"} 40873
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 329223084 (313.97 MB)
telemt_user_octets_to_client{user="hello"} 10669121490 (9.94 GB)
telemt_user_msgs_from_client{user="hello"} 129276
telemt_user_msgs_to_client{user="hello"} 387023
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21445.0 (5h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125670
telemt_connections_bad_total 770
telemt_handshake_timeouts_total 978
telemt_upstream_connect_attempt_total 4415
telemt_upstream_connect_success_total 4393
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 3332
telemt_me_reconnect_success_total 3303
telemt_me_reader_eof_total 3478
telemt_me_idle_close_by_peer_total 3478
telemt_me_route_drop_no_conn_total 50387
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119884
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3343
telemt_me_writer_restored_same_endpoint_total 3296
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 119851
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 2670567168 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 51743598792 (48.19 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 56
```