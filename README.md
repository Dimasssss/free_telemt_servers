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

# Server Metrics 2026-03-15 11:59:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 49517.8 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214199
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 4603
telemt_upstream_connect_attempt_total 12552
telemt_upstream_connect_success_total 12485
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13394
telemt_me_reconnect_success_total 10024
telemt_me_reader_eof_total 10713
telemt_me_idle_close_by_peer_total 10713
telemt_me_route_drop_no_conn_total 422577
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260815
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1502
telemt_desync_full_logged_total 598
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10228
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 9993
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 200072
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 3748927424 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 190505094104 (177.42 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 49523.9 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73615
telemt_connections_bad_total 2360
telemt_handshake_timeouts_total 4587
telemt_upstream_connect_attempt_total 13480
telemt_upstream_connect_success_total 13480
telemt_upstream_connect_attempts_per_request{bucket="1"} 13480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13323
telemt_me_reconnect_success_total 10990
telemt_me_reader_eof_total 11780
telemt_me_idle_close_by_peer_total 11780
telemt_me_route_drop_no_conn_total 33801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64234
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11181
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10974
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 64233
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1163499608 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 27079606400 (25.22 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 49516.7 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79131
telemt_connections_bad_total 1017
telemt_handshake_timeouts_total 2568
telemt_upstream_connect_attempt_total 14093
telemt_upstream_connect_success_total 14085
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13740
telemt_me_reconnect_success_total 11602
telemt_me_reader_eof_total 12437
telemt_me_idle_close_by_peer_total 12437
telemt_me_route_drop_no_conn_total 30202
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72109
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11780
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11594
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 72026
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 9530477964 (8.88 GB)
telemt_user_octets_to_client{user="hello"} 43812592120 (40.80 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 49516.3 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107310
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 697
telemt_upstream_connect_attempt_total 11611
telemt_upstream_connect_success_total 11610
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9203
telemt_me_reconnect_success_total 9157
telemt_me_reader_eof_total 9769
telemt_me_idle_close_by_peer_total 9769
telemt_me_route_drop_no_conn_total 42597
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97868
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 244
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9256
telemt_me_writer_restored_same_endpoint_total 9146
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 97787
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 1738565704 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 54764295468 (51.00 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 24587.6 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56063
telemt_connections_bad_total 14908
telemt_handshake_timeouts_total 853
telemt_upstream_connect_attempt_total 8082
telemt_upstream_connect_success_total 8023
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 101012
telemt_me_reconnect_success_total 6596
telemt_me_reader_eof_total 6865
telemt_me_idle_close_by_peer_total 6865
telemt_me_route_drop_no_conn_total 19697
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39030
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 94
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6584
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6492
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 39167
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 570965061 (544.51 MB)
telemt_user_octets_to_client{user="hello"} 15263767047 (14.22 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 49515.3 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281297
telemt_connections_bad_total 47664
telemt_handshake_timeouts_total 2069
telemt_upstream_connect_attempt_total 10471
telemt_upstream_connect_success_total 10408
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 10471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 7990
telemt_me_reconnect_success_total 7939
telemt_me_reader_eof_total 8450
telemt_me_idle_close_by_peer_total 8450
telemt_me_route_drop_no_conn_total 124420
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223324
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 137
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 8005
telemt_me_writer_restored_same_endpoint_total 7912
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 221686
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 4865661264 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 106807503864 (99.47 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 75
```