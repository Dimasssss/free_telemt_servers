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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 08:01:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 47753.0 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326347
telemt_connections_bad_total 3558
telemt_handshake_timeouts_total 9876
telemt_upstream_connect_attempt_total 9796
telemt_upstream_connect_success_total 9743
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 9796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 7407
telemt_me_reconnect_success_total 7378
telemt_me_reader_eof_total 7846
telemt_me_idle_close_by_peer_total 7846
telemt_me_route_drop_no_conn_total 100048
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294503
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2331
telemt_desync_full_logged_total 659
telemt_desync_suppressed_total 1672
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 1133
telemt_desync_frames_bucket_total{bucket="gt_10"} 660
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7455
telemt_me_writer_restored_same_endpoint_total 7357
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 294254
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 4134087852 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 125402469416 (116.79 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 48004.3 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183126
telemt_connections_bad_total 2351
telemt_handshake_timeouts_total 11928
telemt_upstream_connect_attempt_total 13128
telemt_upstream_connect_success_total 12958
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 13128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 12842
telemt_me_reconnect_success_total 10569
telemt_me_reader_eof_total 11190
telemt_me_idle_close_by_peer_total 11190
telemt_me_route_drop_no_conn_total 66271
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159494
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 405
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10739
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10553
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 159514
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 1947941164 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 63429876664 (59.07 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 47781.1 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112315
telemt_connections_bad_total 6190
telemt_handshake_timeouts_total 5271
telemt_upstream_connect_attempt_total 12440
telemt_upstream_connect_success_total 12376
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 10039
telemt_me_reconnect_success_total 9979
telemt_me_reader_eof_total 10685
telemt_me_idle_close_by_peer_total 10685
telemt_me_route_drop_no_conn_total 34879
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92067
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10104
telemt_me_writer_restored_same_endpoint_total 9968
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 92021
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 6508553476 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 29087352572 (27.09 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 47839.7 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218624
telemt_connections_bad_total 6061
telemt_handshake_timeouts_total 10133
telemt_upstream_connect_attempt_total 11033
telemt_upstream_connect_success_total 10938
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 9540
telemt_me_reconnect_success_total 8475
telemt_me_reader_eof_total 9015
telemt_me_idle_close_by_peer_total 9015
telemt_me_route_drop_no_conn_total 64818
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184607
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 375
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8630
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8467
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 184612
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 1934013038 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 83543188997 (77.81 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 47811.6 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139170
telemt_connections_bad_total 38940
telemt_handshake_timeouts_total 2572
telemt_upstream_connect_attempt_total 14703
telemt_upstream_connect_success_total 14507
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_reconnect_attempts_total 15264
telemt_me_reconnect_success_total 12001
telemt_me_reader_eof_total 12647
telemt_me_idle_close_by_peer_total 12647
telemt_me_route_drop_no_conn_total 36520
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93280
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 174
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12250
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11993
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 93319
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 968725743 (923.85 MB)
telemt_user_octets_to_client{user="hello"} 43951278478 (40.93 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 47972.8 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330440
telemt_connections_bad_total 42190
telemt_handshake_timeouts_total 3037
telemt_upstream_connect_attempt_total 9946
telemt_upstream_connect_success_total 9893
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 9946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11366
telemt_me_reconnect_success_total 7491
telemt_me_reader_eof_total 8099
telemt_me_idle_close_by_peer_total 8099
telemt_me_route_drop_no_conn_total 244805
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350351
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 393
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7720
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7477
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 272278
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 3832372880 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 167089630288 (155.61 GB)
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35979.2 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1915
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17830
telemt_upstream_connect_success_total 17828
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 16069
telemt_me_reconnect_success_total 15977
telemt_me_reader_eof_total 17472
telemt_me_idle_close_by_peer_total 17472
telemt_me_route_drop_no_conn_total 277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1703
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16118
telemt_me_writer_restored_same_endpoint_total 15977
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 1703
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 226554720 (216.06 MB)
telemt_user_octets_to_client{user="hello"} 16897459360 (15.74 GB)
telemt_user_unique_ips_current{user="hello"} 6
```