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

# Server Metrics 2026-03-16 06:07:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 114750.8 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498295
telemt_connections_bad_total 5504
telemt_handshake_timeouts_total 18446
telemt_upstream_connect_attempt_total 27253
telemt_upstream_connect_success_total 27127
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 27253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24874
telemt_me_reconnect_success_total 21444
telemt_me_reader_eof_total 22944
telemt_me_idle_close_by_peer_total 22944
telemt_me_route_drop_no_conn_total 512904
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514655
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2502
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 1499
telemt_desync_frames_bucket_total{bucket="1_2"} 507
telemt_desync_frames_bucket_total{bucket="3_10"} 982
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 111
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21782
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21410
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 338
telemt_user_connections_total{user="hello"} 453505
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 8995791752 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 306362314632 (285.32 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 114758.1 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201098
telemt_connections_bad_total 3114
telemt_handshake_timeouts_total 14878
telemt_upstream_connect_attempt_total 30989
telemt_upstream_connect_success_total 30914
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 30989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 31728
telemt_me_reconnect_success_total 24814
telemt_me_reader_eof_total 26602
telemt_me_idle_close_by_peer_total 26601
telemt_me_route_drop_no_conn_total 101074
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175720
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 66
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 25371
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 24798
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 557
telemt_user_connections_total{user="hello"} 175260
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 3935498609 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 90913226664 (84.67 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 114750.5 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221203
telemt_connections_bad_total 3874
telemt_handshake_timeouts_total 4209
telemt_upstream_connect_attempt_total 32110
telemt_upstream_connect_success_total 32102
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 33752
telemt_me_reconnect_success_total 26357
telemt_me_reader_eof_total 28393
telemt_me_idle_close_by_peer_total 28392
telemt_me_route_drop_no_conn_total 78398
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175713
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26846
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26349
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 175436
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 16776954073 (15.62 GB)
telemt_user_octets_to_client{user="hello"} 106859870916 (99.52 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 114750.3 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294304
telemt_connections_bad_total 1291
telemt_handshake_timeouts_total 2672
telemt_upstream_connect_attempt_total 26733
telemt_upstream_connect_success_total 26706
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 26733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21146
telemt_me_reconnect_success_total 21019
telemt_me_reader_eof_total 22443
telemt_me_idle_close_by_peer_total 22442
telemt_me_route_drop_no_conn_total 106599
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270443
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 955
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 21283
telemt_me_writer_restored_same_endpoint_total 21008
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 270331
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 4517915984 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 118516267352 (110.38 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 89821.7 (24h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198180
telemt_connections_bad_total 34822
telemt_handshake_timeouts_total 3552
telemt_upstream_connect_attempt_total 25615
telemt_upstream_connect_success_total 25474
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 25615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 115339
telemt_me_reconnect_success_total 20858
telemt_me_reader_eof_total 22157
telemt_me_idle_close_by_peer_total 22157
telemt_me_route_drop_no_conn_total 62480
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154813
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 399
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 306
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 21025
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 20754
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 154446
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 2069705769 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 67860738447 (63.20 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 114749.5 (31h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741164
telemt_connections_bad_total 64422
telemt_handshake_timeouts_total 5574
telemt_upstream_connect_attempt_total 24262
telemt_upstream_connect_success_total 24132
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 24262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19758
telemt_me_reconnect_success_total 18417
telemt_me_reader_eof_total 19668
telemt_me_idle_close_by_peer_total 19668
telemt_me_route_drop_no_conn_total 617663
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 749327
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18673
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18390
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 607992
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 13729777668 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 371988090416 (346.44 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 73
```