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

# Server Metrics 2026-03-13 03:07:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 70434.7 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 276152
telemt_connections_bad_total 2915
telemt_handshake_timeouts_total 5697
telemt_upstream_connect_attempt_total 17856
telemt_upstream_connect_success_total 17777
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 17856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1525
telemt_me_reconnect_attempts_total 17701
telemt_me_reconnect_success_total 14216
telemt_me_reader_eof_total 15197
telemt_me_idle_close_by_peer_total 15196
telemt_me_route_drop_no_conn_total 85983
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230214
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14480
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14200
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 230041
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 4064869624 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 112692200936 (104.95 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 70327.7 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127478
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 38825
telemt_upstream_connect_success_total 38350
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 38824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_keepalive_timeout_total 513
telemt_me_reconnect_attempts_total 63711
telemt_me_reconnect_success_total 18307
telemt_me_reader_eof_total 20219
telemt_me_idle_close_by_peer_total 20219
telemt_me_route_drop_no_conn_total 45824
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104558
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 19864
telemt_me_refill_failed_total 1417
telemt_me_writer_restored_same_endpoint_total 18292
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1557
telemt_user_connections_total{user="hello"} 121058
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 1270385644 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35806133099 (33.35 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 70291.2 (19h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153436
telemt_connections_bad_total 1824
telemt_handshake_timeouts_total 2430
telemt_upstream_connect_attempt_total 19503
telemt_upstream_connect_success_total 19501
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 389
telemt_me_reconnect_attempts_total 17077
telemt_me_reconnect_success_total 15916
telemt_me_reader_eof_total 17018
telemt_me_idle_close_by_peer_total 17018
telemt_me_route_drop_no_conn_total 58845
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143510
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 16091
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15896
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 143436
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2732474144 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 68674083108 (63.96 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 70266.9 (19h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220036
telemt_connections_bad_total 13466
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 31816
telemt_upstream_connect_success_total 21992
telemt_upstream_connect_fail_total 9823
telemt_upstream_connect_attempts_per_request{bucket="1"} 31815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9823
telemt_me_keepalive_timeout_total 3294
telemt_me_reconnect_attempts_total 57789
telemt_me_reconnect_success_total 15608
telemt_me_reader_eof_total 17428
telemt_me_idle_close_by_peer_total 17421
telemt_me_route_drop_no_conn_total 80081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183169
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_me_writer_removed_unexpected_total 17140
telemt_me_refill_failed_total 1314
telemt_me_writer_restored_same_endpoint_total 15598
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1532
telemt_user_connections_total{user="hello"} 185920
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 3129513586 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 76072934237 (70.85 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20438.6 (5h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19402
telemt_connections_bad_total 3835
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6259
telemt_upstream_connect_success_total 6202
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 5189
telemt_me_reconnect_success_total 5172
telemt_me_reader_eof_total 5548
telemt_me_idle_close_by_peer_total 5548
telemt_me_route_drop_no_conn_total 5589
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15000
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5213
telemt_me_writer_restored_same_endpoint_total 5156
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 15000
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 112204932 (107.01 MB)
telemt_user_octets_to_client{user="hello"} 6907319356 (6.43 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 70223.4 (19h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371095
telemt_connections_bad_total 6633
telemt_handshake_timeouts_total 2858
telemt_upstream_connect_attempt_total 14939
telemt_upstream_connect_success_total 14855
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7895
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 14994
telemt_me_reconnect_success_total 11373
telemt_me_reader_eof_total 12208
telemt_me_idle_close_by_peer_total 12205
telemt_me_route_drop_no_conn_total 166314
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362822
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11626
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11366
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 351068
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 5925945760 (5.52 GB)
telemt_user_octets_to_client{user="hello"} 212625164660 (198.02 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 22
```