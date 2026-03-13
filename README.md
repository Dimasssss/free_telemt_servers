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

# Server Metrics 2026-03-13 12:57:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 105867.0 (29h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434015
telemt_connections_bad_total 3212
telemt_handshake_timeouts_total 8422
telemt_upstream_connect_attempt_total 26833
telemt_upstream_connect_success_total 26706
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 26833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2398
telemt_me_reconnect_attempts_total 24927
telemt_me_reconnect_success_total 21402
telemt_me_reader_eof_total 22849
telemt_me_idle_close_by_peer_total 22848
telemt_me_route_drop_no_conn_total 137672
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1284
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 829
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 21733
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21386
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 377467
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 6771459804 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 163679417028 (152.44 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 105760.0 (29h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200969
telemt_connections_bad_total 1666
telemt_handshake_timeouts_total 1489
telemt_upstream_connect_attempt_total 62091
telemt_upstream_connect_success_total 61378
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 62091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 1370
telemt_me_reconnect_attempts_total 99743
telemt_me_reconnect_success_total 25974
telemt_me_reader_eof_total 29039
telemt_me_idle_close_by_peer_total 29039
telemt_me_route_drop_no_conn_total 79324
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159761
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 24
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
telemt_me_writer_removed_unexpected_total 28503
telemt_me_refill_failed_total 2301
telemt_me_writer_restored_same_endpoint_total 25957
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2529
telemt_user_connections_total{user="hello"} 189655
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 1942502889 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 62302655694 (58.02 GB)
telemt_user_msgs_from_client{user="hello"} 458147
telemt_user_msgs_to_client{user="hello"} 3222788
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 105723.8 (29h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244571
telemt_connections_bad_total 2070
telemt_handshake_timeouts_total 8652
telemt_upstream_connect_attempt_total 28604
telemt_upstream_connect_success_total 28600
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2210
telemt_me_reconnect_attempts_total 24470
telemt_me_reconnect_success_total 23258
telemt_me_reader_eof_total 24918
telemt_me_idle_close_by_peer_total 24918
telemt_me_route_drop_no_conn_total 90351
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224961
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
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 23512
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23238
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 224875
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 9405033948 (8.76 GB)
telemt_user_octets_to_client{user="hello"} 98522790328 (91.76 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 105699.3 (29h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340725
telemt_connections_bad_total 15024
telemt_handshake_timeouts_total 2499
telemt_upstream_connect_attempt_total 40409
telemt_upstream_connect_success_total 30317
telemt_upstream_connect_fail_total 10092
telemt_upstream_connect_attempts_per_request{bucket="1"} 40409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10092
telemt_me_keepalive_timeout_total 4083
telemt_me_reconnect_attempts_total 93524
telemt_me_reconnect_success_total 21970
telemt_me_reader_eof_total 24872
telemt_me_idle_close_by_peer_total 24865
telemt_me_route_drop_no_conn_total 122560
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293748
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1053
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 744
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24480
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21960
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2510
telemt_user_connections_total{user="hello"} 296659
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 6008372410 (5.60 GB)
telemt_user_octets_to_client{user="hello"} 111895953173 (104.21 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 55870.8 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82253
telemt_connections_bad_total 11060
telemt_handshake_timeouts_total 1187
telemt_upstream_connect_attempt_total 23860
telemt_upstream_connect_success_total 23672
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 23860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 970
telemt_me_reconnect_attempts_total 25870
telemt_me_reconnect_success_total 15952
telemt_me_reader_eof_total 17120
telemt_me_idle_close_by_peer_total 17120
telemt_me_route_drop_no_conn_total 24435
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62463
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 157
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 16401
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15934
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 67372
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 584499977 (557.42 MB)
telemt_user_octets_to_client{user="hello"} 18461010167 (17.19 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 105655.8 (29h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 608157
telemt_connections_bad_total 17862
telemt_handshake_timeouts_total 15811
telemt_upstream_connect_attempt_total 22405
telemt_upstream_connect_success_total 22290
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 22405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 2503
telemt_me_reconnect_attempts_total 21644
telemt_me_reconnect_success_total 17021
telemt_me_reader_eof_total 18275
telemt_me_idle_close_by_peer_total 18272
telemt_me_route_drop_no_conn_total 298133
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580845
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 471
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 17386
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17014
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 553894
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 9797161596 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 292675744196 (272.58 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 69
```