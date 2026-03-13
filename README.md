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

# Server Metrics 2026-03-13 04:18:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 74732.5 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286200
telemt_connections_bad_total 3026
telemt_handshake_timeouts_total 5766
telemt_upstream_connect_attempt_total 18863
telemt_upstream_connect_success_total 18778
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 18863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1534
telemt_me_reconnect_attempts_total 18524
telemt_me_reconnect_success_total 15035
telemt_me_reader_eof_total 16067
telemt_me_idle_close_by_peer_total 16066
telemt_me_route_drop_no_conn_total 89121
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239669
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 794
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 15307
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15019
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 239608
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 4166041352 (3.88 GB)
telemt_user_octets_to_client{user="hello"} 117898717256 (109.80 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74626.1 (20h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131846
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 40306
telemt_upstream_connect_success_total 39810
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 40306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 504
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 66149
telemt_me_reconnect_success_total 19588
telemt_me_reader_eof_total 21616
telemt_me_idle_close_by_peer_total 21616
telemt_me_route_drop_no_conn_total 48187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108771
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 21191
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19573
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1603
telemt_user_connections_total{user="hello"} 125271
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1300973100 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 37650196655 (35.06 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 74589.5 (20h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158925
telemt_connections_bad_total 1843
telemt_handshake_timeouts_total 2581
telemt_upstream_connect_attempt_total 20631
telemt_upstream_connect_success_total 20629
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 416
telemt_me_reconnect_attempts_total 18030
telemt_me_reconnect_success_total 16866
telemt_me_reader_eof_total 18056
telemt_me_idle_close_by_peer_total 18056
telemt_me_route_drop_no_conn_total 61673
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148644
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17052
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16846
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 148569
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 2795084436 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 69643684888 (64.86 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 74565.3 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228635
telemt_connections_bad_total 13473
telemt_handshake_timeouts_total 1455
telemt_upstream_connect_attempt_total 33106
telemt_upstream_connect_success_total 23251
telemt_upstream_connect_fail_total 9855
telemt_upstream_connect_attempts_per_request{bucket="1"} 33106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9855
telemt_me_keepalive_timeout_total 3308
telemt_me_reconnect_attempts_total 61350
telemt_me_reconnect_success_total 16670
telemt_me_reader_eof_total 18589
telemt_me_idle_close_by_peer_total 18582
telemt_me_route_drop_no_conn_total 83493
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191090
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18290
telemt_me_refill_failed_total 1392
telemt_me_writer_restored_same_endpoint_total 16660
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1620
telemt_user_connections_total{user="hello"} 193838
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 3210686266 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 78495067933 (73.10 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24737.0 (6h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24719
telemt_connections_bad_total 4634
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 7743
telemt_upstream_connect_success_total 7669
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 7743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 6440
telemt_me_reconnect_success_total 6417
telemt_me_reader_eof_total 6869
telemt_me_idle_close_by_peer_total 6869
telemt_me_route_drop_no_conn_total 6916
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19293
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6474
telemt_me_writer_restored_same_endpoint_total 6399
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 19293
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 140280236 (133.78 MB)
telemt_user_octets_to_client{user="hello"} 8941140100 (8.33 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74521.7 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385087
telemt_connections_bad_total 7640
telemt_handshake_timeouts_total 2908
telemt_upstream_connect_attempt_total 15846
telemt_upstream_connect_success_total 15760
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1428
telemt_me_reconnect_attempts_total 15687
telemt_me_reconnect_success_total 12060
telemt_me_reader_eof_total 12949
telemt_me_idle_close_by_peer_total 12946
telemt_me_route_drop_no_conn_total 172080
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375514
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
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12328
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12053
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 363760
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 6061209724 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 217568642112 (202.63 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 36
```