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

# Server Metrics 2026-03-13 12:17:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 103423.7 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420894
telemt_connections_bad_total 3210
telemt_handshake_timeouts_total 8359
telemt_upstream_connect_attempt_total 26259
telemt_upstream_connect_success_total 26136
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 26259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2393
telemt_me_reconnect_attempts_total 24486
telemt_me_reconnect_success_total 20961
telemt_me_reader_eof_total 22357
telemt_me_idle_close_by_peer_total 22356
telemt_me_route_drop_no_conn_total 133554
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365275
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1223
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 788
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 526
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 21287
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 20945
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 364868
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 6463662440 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 156544498112 (145.79 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 103317.4 (28h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194236
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 56499
telemt_upstream_connect_success_total 55804
telemt_upstream_connect_fail_total 695
telemt_upstream_connect_attempts_per_request{bucket="1"} 56499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 695
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 95585
telemt_me_reconnect_success_total 25945
telemt_me_reader_eof_total 28881
telemt_me_idle_close_by_peer_total 28881
telemt_me_route_drop_no_conn_total 79016
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158653
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28345
telemt_me_refill_failed_total 2172
telemt_me_writer_restored_same_endpoint_total 25928
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2400
telemt_user_connections_total{user="hello"} 183132
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 1863425148 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 59639418685 (55.54 GB)
telemt_user_msgs_from_client{user="hello"} 358656
telemt_user_msgs_to_client{user="hello"} 2570605
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 103280.9 (28h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236087
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 7268
telemt_upstream_connect_attempt_total 28049
telemt_upstream_connect_success_total 28045
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2172
telemt_me_reconnect_attempts_total 24045
telemt_me_reconnect_success_total 22834
telemt_me_reader_eof_total 24459
telemt_me_idle_close_by_peer_total 24459
telemt_me_route_drop_no_conn_total 87548
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218159
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 23086
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22814
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 218073
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 9342205936 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 97326051672 (90.64 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 103256.4 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329092
telemt_connections_bad_total 13766
telemt_handshake_timeouts_total 2404
telemt_upstream_connect_attempt_total 39899
telemt_upstream_connect_success_total 29824
telemt_upstream_connect_fail_total 10075
telemt_upstream_connect_attempts_per_request{bucket="1"} 39899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10075
telemt_me_keepalive_timeout_total 4048
telemt_me_reconnect_attempts_total 93160
telemt_me_reconnect_success_total 21608
telemt_me_reader_eof_total 24490
telemt_me_idle_close_by_peer_total 24483
telemt_me_route_drop_no_conn_total 119117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283980
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 982
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 690
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 360
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 24112
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21598
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2504
telemt_user_connections_total{user="hello"} 286892
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 5935384598 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 108376476817 (100.93 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 53428.0 (14h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77571
telemt_connections_bad_total 10569
telemt_handshake_timeouts_total 810
telemt_upstream_connect_attempt_total 23238
telemt_upstream_connect_success_total 23057
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 23238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 940
telemt_me_reconnect_attempts_total 25367
telemt_me_reconnect_success_total 15450
telemt_me_reader_eof_total 16589
telemt_me_idle_close_by_peer_total 16589
telemt_me_route_drop_no_conn_total 22954
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58775
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 107
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 15895
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15432
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 63686
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 555655941 (529.91 MB)
telemt_user_octets_to_client{user="hello"} 17998013711 (16.76 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 103213.1 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588779
telemt_connections_bad_total 17431
telemt_handshake_timeouts_total 13779
telemt_upstream_connect_attempt_total 21910
telemt_upstream_connect_success_total 21796
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 21910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2486
telemt_me_reconnect_attempts_total 21280
telemt_me_reconnect_success_total 16659
telemt_me_reader_eof_total 17880
telemt_me_idle_close_by_peer_total 17877
telemt_me_route_drop_no_conn_total 290840
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564416
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17021
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16652
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 537479
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 9565469132 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 287745196656 (267.98 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 68
```