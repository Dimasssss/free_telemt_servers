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

# Server Metrics 2026-03-13 01:04:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 63067.6 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261115
telemt_connections_bad_total 2766
telemt_handshake_timeouts_total 5592
telemt_upstream_connect_attempt_total 15906
telemt_upstream_connect_success_total 15837
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 15906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8788
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1505
telemt_me_reconnect_attempts_total 16122
telemt_me_reconnect_success_total 12648
telemt_me_reader_eof_total 13486
telemt_me_idle_close_by_peer_total 13485
telemt_me_route_drop_no_conn_total 81229
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216094
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 727
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12895
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12632
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 215862
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 3920956112 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 109046016528 (101.56 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 62960.6 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120974
telemt_connections_bad_total 732
telemt_handshake_timeouts_total 971
telemt_upstream_connect_attempt_total 35583
telemt_upstream_connect_success_total 35156
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 35583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_keepalive_timeout_total 453
telemt_me_reconnect_attempts_total 59720
telemt_me_reconnect_success_total 15510
telemt_me_reader_eof_total 17280
telemt_me_idle_close_by_peer_total 17280
telemt_me_route_drop_no_conn_total 43188
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98316
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 17005
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 15495
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1495
telemt_user_connections_total{user="hello"} 114816
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1238382808 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34738306727 (32.35 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 62924.4 (17h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146256
telemt_connections_bad_total 1681
telemt_handshake_timeouts_total 2332
telemt_upstream_connect_attempt_total 17343
telemt_upstream_connect_success_total 17341
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 363
telemt_me_reconnect_attempts_total 15308
telemt_me_reconnect_success_total 14153
telemt_me_reader_eof_total 15111
telemt_me_idle_close_by_peer_total 15111
telemt_me_route_drop_no_conn_total 55553
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136769
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14312
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14133
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 136733
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 2629036184 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62280666736 (58.00 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 62900.0 (17h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209614
telemt_connections_bad_total 13296
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 29372
telemt_upstream_connect_success_total 19611
telemt_upstream_connect_fail_total 9761
telemt_upstream_connect_attempts_per_request{bucket="1"} 29372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9761
telemt_me_keepalive_timeout_total 3206
telemt_me_reconnect_attempts_total 50496
telemt_me_reconnect_success_total 13599
telemt_me_reader_eof_total 15216
telemt_me_idle_close_by_peer_total 15209
telemt_me_route_drop_no_conn_total 75325
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173395
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14955
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 13589
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1356
telemt_user_connections_total{user="hello"} 176147
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 3019014182 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 72482984345 (67.51 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13071.6 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11880
telemt_connections_bad_total 2485
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 4087
telemt_upstream_connect_success_total 4050
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 4087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 3380
telemt_me_reconnect_success_total 3371
telemt_me_reader_eof_total 3594
telemt_me_idle_close_by_peer_total 3594
telemt_me_route_drop_no_conn_total 3570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8990
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3390
telemt_me_writer_restored_same_endpoint_total 3355
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 8990
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 35350492 (33.71 MB)
telemt_user_octets_to_client{user="hello"} 2780623736 (2.59 GB)
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 62856.5 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351388
telemt_connections_bad_total 6543
telemt_handshake_timeouts_total 2597
telemt_upstream_connect_attempt_total 13277
telemt_upstream_connect_success_total 13206
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1334
telemt_me_reconnect_attempts_total 13695
telemt_me_reconnect_success_total 10078
telemt_me_reader_eof_total 10810
telemt_me_idle_close_by_peer_total 10808
telemt_me_route_drop_no_conn_total 156899
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343848
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10314
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10071
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 332150
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 5631884400 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 179997808480 (167.64 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 39
```