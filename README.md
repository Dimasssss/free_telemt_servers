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

# Server Metrics 2026-03-16 17:57:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 15546.0 (4h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157284
telemt_connections_bad_total 678
telemt_handshake_timeouts_total 4035
telemt_upstream_connect_attempt_total 3359
telemt_upstream_connect_success_total 3346
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3672
telemt_me_reconnect_success_total 2502
telemt_me_reader_eof_total 2600
telemt_me_idle_close_by_peer_total 2599
telemt_me_route_drop_no_conn_total 47667
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147360
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 722
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 551
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 256
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2554
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2500
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 147274
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 2680565724 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 83593565772 (77.85 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 10324.9 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73233
telemt_connections_bad_total 624
telemt_handshake_timeouts_total 3198
telemt_upstream_connect_attempt_total 2225
telemt_upstream_connect_success_total 2212
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 5150
telemt_me_reconnect_success_total 1641
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1785
telemt_me_route_drop_no_conn_total 41656
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66756
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1780
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1636
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 66697
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 801315896 (764.19 MB)
telemt_user_octets_to_client{user="hello"} 19599370276 (18.25 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 15659.1 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63251
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 4695
telemt_upstream_connect_success_total 4648
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 4695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 41704
telemt_me_reconnect_success_total 2819
telemt_me_reader_eof_total 3170
telemt_me_idle_close_by_peer_total 3170
telemt_me_route_drop_no_conn_total 22135
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58309
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 162
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3154
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2775
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 59248
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 793474218 (756.72 MB)
telemt_user_octets_to_client{user="hello"} 16587781270 (15.45 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 15795.4 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122848
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1761
telemt_upstream_connect_attempt_total 3403
telemt_upstream_connect_success_total 3377
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8856
telemt_me_reconnect_success_total 2500
telemt_me_reader_eof_total 2750
telemt_me_idle_close_by_peer_total 2749
telemt_me_route_drop_no_conn_total 45138
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116550
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 652
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 269
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2731
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2496
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 116519
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 1591473404 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 29148544228 (27.15 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 13255.7 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70859
telemt_connections_bad_total 20342
telemt_handshake_timeouts_total 567
telemt_upstream_connect_attempt_total 3474
telemt_upstream_connect_success_total 3420
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 3474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 4382
telemt_me_reconnect_success_total 2719
telemt_me_reader_eof_total 2806
telemt_me_idle_close_by_peer_total 2806
telemt_me_route_drop_no_conn_total 50940
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66341
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2872
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2719
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 47384
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 2061784592 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 32678878840 (30.43 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 15366.0 (4h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177983
telemt_connections_bad_total 2168
telemt_handshake_timeouts_total 3390
telemt_upstream_connect_attempt_total 3163
telemt_upstream_connect_success_total 3163
telemt_upstream_connect_attempts_per_request{bucket="1"} 3163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1634
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 2346
telemt_me_reader_eof_total 2553
telemt_me_idle_close_by_peer_total 2552
telemt_me_route_drop_no_conn_total 79579
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165165
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 84
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2522
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2340
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 164833
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 3186688468 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 63418754908 (59.06 GB)
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 80
```