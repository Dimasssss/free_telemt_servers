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

# Server Metrics 2026-03-16 09:05:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 125476.5 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595955
telemt_connections_bad_total 8949
telemt_handshake_timeouts_total 20782
telemt_upstream_connect_attempt_total 29352
telemt_upstream_connect_success_total 29211
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 29352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 26431
telemt_me_reconnect_success_total 22991
telemt_me_reader_eof_total 24571
telemt_me_idle_close_by_peer_total 24571
telemt_me_route_drop_no_conn_total 534007
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586929
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2772
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 1686
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1097
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23351
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22957
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 360
telemt_user_connections_total{user="hello"} 525737
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 10167514780 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 331213987844 (308.47 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 125485.4 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243487
telemt_connections_bad_total 3285
telemt_handshake_timeouts_total 15248
telemt_upstream_connect_attempt_total 33626
telemt_upstream_connect_success_total 33551
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 667
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36201
telemt_me_reconnect_success_total 26911
telemt_me_reader_eof_total 28865
telemt_me_idle_close_by_peer_total 28864
telemt_me_route_drop_no_conn_total 117249
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216534
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27576
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26895
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 216071
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 4821112249 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 119711031676 (111.49 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 125476.5 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255066
telemt_connections_bad_total 5749
telemt_handshake_timeouts_total 5196
telemt_upstream_connect_attempt_total 34930
telemt_upstream_connect_success_total 34922
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 34930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36042
telemt_me_reconnect_success_total 28629
telemt_me_reader_eof_total 30794
telemt_me_idle_close_by_peer_total 30793
telemt_me_route_drop_no_conn_total 88603
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205898
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 29143
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28621
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 205599
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 17631235793 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 115608111216 (107.67 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 125475.7 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 360806
telemt_connections_bad_total 1375
telemt_handshake_timeouts_total 3140
telemt_upstream_connect_attempt_total 29000
telemt_upstream_connect_success_total 28964
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 29000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22871
telemt_me_reconnect_success_total 22723
telemt_me_reader_eof_total 24260
telemt_me_idle_close_by_peer_total 24259
telemt_me_route_drop_no_conn_total 125795
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333284
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1220
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 802
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23025
telemt_me_writer_restored_same_endpoint_total 22712
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 333164
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 5232727706 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 138159596044 (128.67 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 100547.1 (27h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231390
telemt_connections_bad_total 36900
telemt_handshake_timeouts_total 4219
telemt_upstream_connect_attempt_total 28649
telemt_upstream_connect_success_total 28492
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 28649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117834
telemt_me_reconnect_success_total 23335
telemt_me_reader_eof_total 24786
telemt_me_idle_close_by_peer_total 24786
telemt_me_route_drop_no_conn_total 72269
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183651
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 459
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 265
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23532
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23231
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 183269
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 2434324133 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 77901103911 (72.55 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 125475.1 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842444
telemt_connections_bad_total 72532
telemt_handshake_timeouts_total 9813
telemt_upstream_connect_attempt_total 26263
telemt_upstream_connect_success_total 26125
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 26263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21228
telemt_me_reconnect_success_total 19877
telemt_me_reader_eof_total 21223
telemt_me_idle_close_by_peer_total 21223
telemt_me_route_drop_no_conn_total 656990
telemt_me_route_drop_channel_closed_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 834177
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
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20156
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19850
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 692804
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 14916780860 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 419034727616 (390.26 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 108
```