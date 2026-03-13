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

# Server Metrics 2026-03-13 01:50:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 65829.7 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266386
telemt_connections_bad_total 2804
telemt_handshake_timeouts_total 5633
telemt_upstream_connect_attempt_total 16662
telemt_upstream_connect_success_total 16591
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1512
telemt_me_reconnect_attempts_total 16730
telemt_me_reconnect_success_total 13252
telemt_me_reader_eof_total 14151
telemt_me_idle_close_by_peer_total 14150
telemt_me_route_drop_no_conn_total 82587
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221138
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 731
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13504
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13236
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 220905
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 3962969352 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 110241432528 (102.67 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 65722.6 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123839
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 36624
telemt_upstream_connect_success_total 36178
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 36624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_keepalive_timeout_total 468
telemt_me_reconnect_attempts_total 60613
telemt_me_reconnect_success_total 16399
telemt_me_reader_eof_total 18210
telemt_me_idle_close_by_peer_total 18210
telemt_me_route_drop_no_conn_total 44260
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101060
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17902
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16384
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 117560
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 1254413696 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35490050939 (33.05 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65686.1 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149218
telemt_connections_bad_total 1725
telemt_handshake_timeouts_total 2351
telemt_upstream_connect_attempt_total 18088
telemt_upstream_connect_success_total 18086
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9666
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 15923
telemt_me_reconnect_success_total 14766
telemt_me_reader_eof_total 15784
telemt_me_idle_close_by_peer_total 15784
telemt_me_route_drop_no_conn_total 56813
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139564
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
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14933
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14746
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 139517
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 2699726448 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 64759768468 (60.31 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65661.9 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213116
telemt_connections_bad_total 13335
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 30263
telemt_upstream_connect_success_total 20490
telemt_upstream_connect_fail_total 9773
telemt_upstream_connect_attempts_per_request{bucket="1"} 30263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9773
telemt_me_keepalive_timeout_total 3221
telemt_me_reconnect_attempts_total 51244
telemt_me_reconnect_success_total 14344
telemt_me_reader_eof_total 15995
telemt_me_idle_close_by_peer_total 15988
telemt_me_route_drop_no_conn_total 76952
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176685
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15703
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14334
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1359
telemt_user_connections_total{user="hello"} 179437
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 3042610994 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 73478918445 (68.43 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15833.5 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14019
telemt_connections_bad_total 2984
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 4920
telemt_upstream_connect_success_total 4877
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 4920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 4078
telemt_me_reconnect_success_total 4068
telemt_me_reader_eof_total 4348
telemt_me_idle_close_by_peer_total 4348
telemt_me_route_drop_no_conn_total 4326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10581
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4095
telemt_me_writer_restored_same_endpoint_total 4052
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 10581
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 52990484 (50.54 MB)
telemt_user_octets_to_client{user="hello"} 4522898772 (4.21 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65618.3 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357760
telemt_connections_bad_total 6579
telemt_handshake_timeouts_total 2637
telemt_upstream_connect_attempt_total 13917
telemt_upstream_connect_success_total 13841
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1346
telemt_me_reconnect_attempts_total 14200
telemt_me_reconnect_success_total 10581
telemt_me_reader_eof_total 11351
telemt_me_idle_close_by_peer_total 11349
telemt_me_route_drop_no_conn_total 160219
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349960
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
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10822
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10574
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 338259
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 5731110996 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 187466509896 (174.59 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 22
```