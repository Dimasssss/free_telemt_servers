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

# Server Metrics 2026-03-12 22:00:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52020.6 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241856
telemt_connections_bad_total 2685
telemt_handshake_timeouts_total 5190
telemt_upstream_connect_attempt_total 13043
telemt_upstream_connect_success_total 12983
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 13043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1465
telemt_me_reconnect_attempts_total 13814
telemt_me_reconnect_success_total 10346
telemt_me_reader_eof_total 11008
telemt_me_idle_close_by_peer_total 11007
telemt_me_route_drop_no_conn_total 74197
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199014
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 676
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 10573
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10330
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 198781
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 3722928488 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 97285952960 (90.60 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 51913.5 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108001
telemt_connections_bad_total 552
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 31025
telemt_upstream_connect_success_total 30687
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 31025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 498
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 52217
telemt_me_reconnect_success_total 11568
telemt_me_reader_eof_total 13105
telemt_me_idle_close_by_peer_total 13105
telemt_me_route_drop_no_conn_total 39098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86235
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 12923
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 11553
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1355
telemt_user_connections_total{user="hello"} 102736
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 1139215524 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 32380310675 (30.16 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 51877.0 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134332
telemt_connections_bad_total 1580
telemt_handshake_timeouts_total 2216
telemt_upstream_connect_attempt_total 14305
telemt_upstream_connect_success_total 14304
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 12786
telemt_me_reconnect_success_total 11645
telemt_me_reader_eof_total 12405
telemt_me_idle_close_by_peer_total 12405
telemt_me_route_drop_no_conn_total 50609
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125435
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 11790
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11625
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 125401
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 2557027172 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 59873311208 (55.76 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 51852.7 (14h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195755
telemt_connections_bad_total 13191
telemt_handshake_timeouts_total 1368
telemt_upstream_connect_attempt_total 25469
telemt_upstream_connect_success_total 15790
telemt_upstream_connect_fail_total 9679
telemt_upstream_connect_attempts_per_request{bucket="1"} 25469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9679
telemt_me_keepalive_timeout_total 2469
telemt_me_reconnect_attempts_total 42548
telemt_me_reconnect_success_total 10304
telemt_me_reader_eof_total 11656
telemt_me_idle_close_by_peer_total 11649
telemt_me_route_drop_no_conn_total 68512
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159970
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 11474
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10294
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1170
telemt_user_connections_total{user="hello"} 162725
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2953638082 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 66938758077 (62.34 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2024.3 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2172
telemt_connections_bad_total 363
telemt_upstream_connect_attempt_total 511
telemt_upstream_connect_success_total 505
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 351
telemt_me_reconnect_success_total 351
telemt_me_reader_eof_total 351
telemt_me_idle_close_by_peer_total 351
telemt_me_route_drop_no_conn_total 691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1682
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 349
telemt_me_writer_restored_same_endpoint_total 335
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 1682
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 5811716 (5.54 MB)
telemt_user_octets_to_client{user="hello"} 1012721644 (965.81 MB)
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 51809.2 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316731
telemt_connections_bad_total 4514
telemt_handshake_timeouts_total 2466
telemt_upstream_connect_attempt_total 10817
telemt_upstream_connect_success_total 10760
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 499
telemt_me_reconnect_attempts_total 11765
telemt_me_reconnect_success_total 8156
telemt_me_reader_eof_total 8712
telemt_me_idle_close_by_peer_total 8711
telemt_me_route_drop_no_conn_total 144036
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311994
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8369
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8149
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 300296
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 5348168588 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 151209069824 (140.82 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 32
```