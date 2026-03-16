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

# Server Metrics 2026-03-16 07:13:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 118733.3 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540941
telemt_connections_bad_total 5702
telemt_handshake_timeouts_total 19003
telemt_upstream_connect_attempt_total 27903
telemt_upstream_connect_success_total 27772
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 27903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25347
telemt_me_reconnect_success_total 21913
telemt_me_reader_eof_total 23447
telemt_me_idle_close_by_peer_total 23447
telemt_me_route_drop_no_conn_total 520460
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539057
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2623
telemt_desync_full_logged_total 1041
telemt_desync_suppressed_total 1582
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 1013
telemt_desync_frames_bucket_total{bucket="gt_10"} 1067
telemt_pool_swap_total 115
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22263
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21879
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 350
telemt_user_connections_total{user="hello"} 477883
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 9351142436 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 314695978564 (293.08 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 118739.5 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214730
telemt_connections_bad_total 3154
telemt_handshake_timeouts_total 15045
telemt_upstream_connect_attempt_total 31889
telemt_upstream_connect_success_total 31814
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32453
telemt_me_reconnect_success_total 25534
telemt_me_reader_eof_total 27355
telemt_me_idle_close_by_peer_total 27354
telemt_me_route_drop_no_conn_total 106371
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188832
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 85
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 26097
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25518
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 188366
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 4364439957 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 104127092776 (96.98 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 118732.3 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234196
telemt_connections_bad_total 5729
telemt_handshake_timeouts_total 4593
telemt_upstream_connect_attempt_total 33095
telemt_upstream_connect_success_total 33087
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34561
telemt_me_reconnect_success_total 27162
telemt_me_reader_eof_total 29241
telemt_me_idle_close_by_peer_total 29240
telemt_me_route_drop_no_conn_total 82107
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186176
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
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 27655
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27154
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 185890
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 17283083557 (16.10 GB)
telemt_user_octets_to_client{user="hello"} 110223356112 (102.65 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 118731.8 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315225
telemt_connections_bad_total 1331
telemt_handshake_timeouts_total 2896
telemt_upstream_connect_attempt_total 27521
telemt_upstream_connect_success_total 27492
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21746
telemt_me_reconnect_success_total 21613
telemt_me_reader_eof_total 23084
telemt_me_idle_close_by_peer_total 23083
telemt_me_route_drop_no_conn_total 112521
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290144
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1009
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 21890
telemt_me_writer_restored_same_endpoint_total 21602
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 290020
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 4721769438 (4.40 GB)
telemt_user_octets_to_client{user="hello"} 125702113420 (117.07 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 93803.2 (26h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210460
telemt_connections_bad_total 35573
telemt_handshake_timeouts_total 3607
telemt_upstream_connect_attempt_total 26779
telemt_upstream_connect_success_total 26632
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 26779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116279
telemt_me_reconnect_success_total 21790
telemt_me_reader_eof_total 23149
telemt_me_idle_close_by_peer_total 23149
telemt_me_route_drop_no_conn_total 65898
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165845
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 480
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21966
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21686
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 165476
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 2297646665 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 71595797475 (66.68 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 118731.0 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 773971
telemt_connections_bad_total 66733
telemt_handshake_timeouts_total 5787
telemt_upstream_connect_attempt_total 24990
telemt_upstream_connect_success_total 24858
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20309
telemt_me_reconnect_success_total 18965
telemt_me_reader_eof_total 20253
telemt_me_idle_close_by_peer_total 20253
telemt_me_route_drop_no_conn_total 631269
telemt_me_route_drop_channel_closed_total 102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 778519
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
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19229
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18938
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 637164
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 14166367136 (13.19 GB)
telemt_user_octets_to_client{user="hello"} 383524723784 (357.19 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 78
```