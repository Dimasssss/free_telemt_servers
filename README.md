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

# Server Metrics 2026-03-15 09:47:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 41552.7 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167671
telemt_connections_bad_total 1168
telemt_handshake_timeouts_total 3959
telemt_upstream_connect_attempt_total 10333
telemt_upstream_connect_success_total 10275
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9400
telemt_me_reconnect_success_total 8186
telemt_me_reader_eof_total 8742
telemt_me_idle_close_by_peer_total 8742
telemt_me_route_drop_no_conn_total 390684
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215342
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1272
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 761
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 554
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8298
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8155
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 156389
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 2185543796 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 166624539756 (155.18 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 41560.6 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53073
telemt_connections_bad_total 2280
telemt_handshake_timeouts_total 3030
telemt_upstream_connect_attempt_total 11267
telemt_upstream_connect_success_total 11267
telemt_upstream_connect_attempts_per_request{bucket="1"} 11267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11471
telemt_me_reconnect_success_total 9154
telemt_me_reader_eof_total 9836
telemt_me_idle_close_by_peer_total 9836
telemt_me_route_drop_no_conn_total 25295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46074
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9321
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9138
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 46073
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 948000432 (904.08 MB)
telemt_user_octets_to_client{user="hello"} 19222268996 (17.90 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 41552.9 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60395
telemt_connections_bad_total 516
telemt_handshake_timeouts_total 2421
telemt_upstream_connect_attempt_total 11328
telemt_upstream_connect_success_total 11327
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 9267
telemt_me_reconnect_success_total 9222
telemt_me_reader_eof_total 9930
telemt_me_idle_close_by_peer_total 9930
telemt_me_route_drop_no_conn_total 22641
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54997
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9306
telemt_me_writer_restored_same_endpoint_total 9218
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 54925
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9232491688 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 35382657792 (32.95 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 41552.8 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76821
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 9920
telemt_upstream_connect_success_total 9919
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7867
telemt_me_reconnect_success_total 7831
telemt_me_reader_eof_total 8363
telemt_me_idle_close_by_peer_total 8363
telemt_me_route_drop_no_conn_total 32655
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69806
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7912
telemt_me_writer_restored_same_endpoint_total 7820
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 69738
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 1386381908 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 45001427344 (41.91 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 16624.1 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27224
telemt_connections_bad_total 3131
telemt_handshake_timeouts_total 355
telemt_upstream_connect_attempt_total 5683
telemt_upstream_connect_success_total 5634
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 5683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 99020
telemt_me_reconnect_success_total 4614
telemt_me_reader_eof_total 4773
telemt_me_idle_close_by_peer_total 4773
telemt_me_route_drop_no_conn_total 8785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23032
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4579
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4510
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 23172
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 265425753 (253.13 MB)
telemt_user_octets_to_client{user="hello"} 11529615491 (10.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 41552.0 (11h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196383
telemt_connections_bad_total 25358
telemt_handshake_timeouts_total 1201
telemt_upstream_connect_attempt_total 8943
telemt_upstream_connect_success_total 8891
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 8943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 6831
telemt_me_reconnect_success_total 6793
telemt_me_reader_eof_total 7247
telemt_me_idle_close_by_peer_total 7247
telemt_me_route_drop_no_conn_total 92476
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6838
telemt_me_writer_restored_same_endpoint_total 6766
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 162918
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 4210136560 (3.92 GB)
telemt_user_octets_to_client{user="hello"} 82354269180 (76.70 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 77
```