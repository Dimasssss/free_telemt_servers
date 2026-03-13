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

# Server Metrics 2026-03-13 08:50:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 91013.7 (25h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354839
telemt_connections_bad_total 3179
telemt_handshake_timeouts_total 7760
telemt_upstream_connect_attempt_total 22838
telemt_upstream_connect_success_total 22729
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 22838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1673
telemt_me_reconnect_attempts_total 21657
telemt_me_reconnect_success_total 18149
telemt_me_reader_eof_total 19390
telemt_me_idle_close_by_peer_total 19389
telemt_me_route_drop_no_conn_total 111722
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303232
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 980
telemt_desync_full_logged_total 364
telemt_desync_suppressed_total 616
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18447
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18133
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 302923
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 4962611924 (4.62 GB)
telemt_user_octets_to_client{user="hello"} 137796834996 (128.33 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 90906.7 (25h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161331
telemt_connections_bad_total 1510
telemt_handshake_timeouts_total 1219
telemt_upstream_connect_attempt_total 45676
telemt_upstream_connect_success_total 45057
telemt_upstream_connect_fail_total 619
telemt_upstream_connect_attempts_per_request{bucket="1"} 45676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 513
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 619
telemt_me_keepalive_timeout_total 698
telemt_me_reconnect_attempts_total 79412
telemt_me_reconnect_success_total 24041
telemt_me_reader_eof_total 26478
telemt_me_idle_close_by_peer_total 26478
telemt_me_route_drop_no_conn_total 61627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135658
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 25966
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24026
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1925
telemt_user_connections_total{user="hello"} 152150
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 1573582736 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 48889963951 (45.53 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 90870.2 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195386
telemt_connections_bad_total 1999
telemt_handshake_timeouts_total 3595
telemt_upstream_connect_attempt_total 24642
telemt_upstream_connect_success_total 24639
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13307
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 21260
telemt_me_reconnect_success_total 20076
telemt_me_reader_eof_total 21527
telemt_me_idle_close_by_peer_total 21527
telemt_me_route_drop_no_conn_total 74476
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182621
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
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 20297
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20056
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 182547
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 6733931148 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 76279819484 (71.04 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 90846.0 (25h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282366
telemt_connections_bad_total 13662
telemt_handshake_timeouts_total 2120
telemt_upstream_connect_attempt_total 37635
telemt_upstream_connect_success_total 27657
telemt_upstream_connect_fail_total 9978
telemt_upstream_connect_attempts_per_request{bucket="1"} 37635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9978
telemt_me_keepalive_timeout_total 3388
telemt_me_reconnect_attempts_total 72942
telemt_me_reconnect_success_total 20276
telemt_me_reader_eof_total 22559
telemt_me_idle_close_by_peer_total 22552
telemt_me_route_drop_no_conn_total 101784
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240456
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 887
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22181
telemt_me_refill_failed_total 1641
telemt_me_writer_restored_same_endpoint_total 20266
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1905
telemt_user_connections_total{user="hello"} 243181
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 5426882102 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 92760955501 (86.39 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 41017.5 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52251
telemt_connections_bad_total 8313
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 14244
telemt_upstream_connect_success_total 14100
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 14244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 14263
telemt_me_reconnect_success_total 12043
telemt_me_reader_eof_total 12834
telemt_me_idle_close_by_peer_total 12834
telemt_me_route_drop_no_conn_total 15748
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42055
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 12216
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12025
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 42053
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 306783132 (292.57 MB)
telemt_user_octets_to_client{user="hello"} 11642404564 (10.84 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90802.4 (25h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484925
telemt_connections_bad_total 13387
telemt_handshake_timeouts_total 4601
telemt_upstream_connect_attempt_total 19163
telemt_upstream_connect_success_total 19060
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1538
telemt_me_reconnect_attempts_total 18208
telemt_me_reconnect_success_total 14565
telemt_me_reader_eof_total 15641
telemt_me_idle_close_by_peer_total 15638
telemt_me_route_drop_no_conn_total 253944
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476640
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 396
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 14865
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14558
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 449734
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 8271162412 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 255858310644 (238.29 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 53
```