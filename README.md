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

# Server Metrics 2026-03-15 21:05:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 82286.1 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382682
telemt_connections_bad_total 5032
telemt_handshake_timeouts_total 13772
telemt_upstream_connect_attempt_total 19662
telemt_upstream_connect_success_total 19564
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 19662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18865
telemt_me_reconnect_success_total 15461
telemt_me_reader_eof_total 16486
telemt_me_idle_close_by_peer_total 16486
telemt_me_route_drop_no_conn_total 481150
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410438
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2018
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 789
telemt_desync_frames_bucket_total{bucket="gt_10"} 851
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 15738
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 15427
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 349500
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 7817624896 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 264472350444 (246.31 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 82292.6 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158748
telemt_connections_bad_total 2868
telemt_handshake_timeouts_total 13956
telemt_upstream_connect_attempt_total 22575
telemt_upstream_connect_success_total 22500
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 22575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 607
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 24869
telemt_me_reconnect_success_total 17984
telemt_me_reader_eof_total 19230
telemt_me_idle_close_by_peer_total 19229
telemt_me_route_drop_no_conn_total 65486
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135332
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 18471
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 17968
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 135602
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2575151253 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 69167305820 (64.42 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 82285.2 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157637
telemt_connections_bad_total 1736
telemt_handshake_timeouts_total 3395
telemt_upstream_connect_attempt_total 23591
telemt_upstream_connect_success_total 23583
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 23591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 26791
telemt_me_reconnect_success_total 19424
telemt_me_reader_eof_total 20869
telemt_me_idle_close_by_peer_total 20868
telemt_me_route_drop_no_conn_total 62732
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140102
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 19843
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 19416
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 139984
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 10943624428 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 82764371296 (77.08 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 82284.8 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228729
telemt_connections_bad_total 1186
telemt_handshake_timeouts_total 1581
telemt_upstream_connect_attempt_total 19216
telemt_upstream_connect_success_total 19198
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 19216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 15190
telemt_me_reconnect_success_total 15097
telemt_me_reader_eof_total 16087
telemt_me_idle_close_by_peer_total 16087
telemt_me_route_drop_no_conn_total 83616
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210541
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 786
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 509
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15280
telemt_me_writer_restored_same_endpoint_total 15086
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 210459
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 3971383384 (3.70 GB)
telemt_user_octets_to_client{user="hello"} 96664649856 (90.03 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 57356.4 (15h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139599
telemt_connections_bad_total 26769
telemt_handshake_timeouts_total 2537
telemt_upstream_connect_attempt_total 16656
telemt_upstream_connect_success_total 16556
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 16656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107977
telemt_me_reconnect_success_total 13523
telemt_me_reader_eof_total 14241
telemt_me_idle_close_by_peer_total 14241
telemt_me_route_drop_no_conn_total 46438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106434
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 13615
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 13419
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 106562
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1669483333 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 40656987663 (37.86 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 82284.3 (22h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555167
telemt_connections_bad_total 58525
telemt_handshake_timeouts_total 4362
telemt_upstream_connect_attempt_total 17450
telemt_upstream_connect_success_total 17352
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 17450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 14533
telemt_me_reconnect_success_total 13221
telemt_me_reader_eof_total 14059
telemt_me_idle_close_by_peer_total 14059
telemt_me_route_drop_no_conn_total 410463
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549592
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13405
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 13194
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 471483
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 11827469444 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 274335165860 (255.49 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 44
```