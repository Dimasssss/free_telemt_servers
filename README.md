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

# Server Metrics 2026-03-12 22:41:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 54475.4 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246440
telemt_connections_bad_total 2691
telemt_handshake_timeouts_total 5249
telemt_upstream_connect_attempt_total 13687
telemt_upstream_connect_success_total 13625
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 13687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1473
telemt_me_reconnect_attempts_total 14327
telemt_me_reconnect_success_total 10859
telemt_me_reader_eof_total 11565
telemt_me_idle_close_by_peer_total 11564
telemt_me_route_drop_no_conn_total 75928
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202907
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11088
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10843
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 202673
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 3785838708 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 99603864060 (92.76 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 54368.5 (15h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110470
telemt_connections_bad_total 565
telemt_handshake_timeouts_total 817
telemt_upstream_connect_attempt_total 32179
telemt_upstream_connect_success_total 31820
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 32179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 499
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 396
telemt_me_reconnect_attempts_total 54437
telemt_me_reconnect_success_total 12570
telemt_me_reader_eof_total 14150
telemt_me_idle_close_by_peer_total 14150
telemt_me_route_drop_no_conn_total 40231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88596
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
telemt_me_writer_removed_unexpected_total 13968
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 12555
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1398
telemt_user_connections_total{user="hello"} 105097
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1175036680 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 33595969067 (31.29 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 54332.1 (15h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136814
telemt_connections_bad_total 1602
telemt_handshake_timeouts_total 2220
telemt_upstream_connect_attempt_total 14970
telemt_upstream_connect_success_total 14969
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14970
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 13322
telemt_me_reconnect_success_total 12178
telemt_me_reader_eof_total 12989
telemt_me_idle_close_by_peer_total 12989
telemt_me_route_drop_no_conn_total 51351
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127829
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12330
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 12158
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 127796
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 2574033540 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 60197309480 (56.06 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 54307.7 (15h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199837
telemt_connections_bad_total 13240
telemt_handshake_timeouts_total 1371
telemt_upstream_connect_attempt_total 26297
telemt_upstream_connect_success_total 16607
telemt_upstream_connect_fail_total 9690
telemt_upstream_connect_attempts_per_request{bucket="1"} 26297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7601
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9690
telemt_me_keepalive_timeout_total 2481
telemt_me_reconnect_attempts_total 43235
telemt_me_reconnect_success_total 10989
telemt_me_reader_eof_total 12395
telemt_me_idle_close_by_peer_total 12388
telemt_me_route_drop_no_conn_total 70136
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163958
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 12168
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10979
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1179
telemt_user_connections_total{user="hello"} 166712
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2971110018 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 67951657741 (63.28 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4479.3 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4296
telemt_connections_bad_total 804
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1252
telemt_upstream_connect_success_total 1242
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1002
telemt_me_reconnect_success_total 1002
telemt_me_reader_eof_total 1045
telemt_me_idle_close_by_peer_total 1045
telemt_me_route_drop_no_conn_total 1125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3326
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1005
telemt_me_writer_restored_same_endpoint_total 986
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 3326
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 9257020 (8.83 MB)
telemt_user_octets_to_client{user="hello"} 1169590916 (1.09 GB)
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 54264.2 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324460
telemt_connections_bad_total 5096
telemt_handshake_timeouts_total 2489
telemt_upstream_connect_attempt_total 11374
telemt_upstream_connect_success_total 11312
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 505
telemt_me_reconnect_attempts_total 12188
telemt_me_reconnect_success_total 8578
telemt_me_reader_eof_total 9170
telemt_me_idle_close_by_peer_total 9169
telemt_me_route_drop_no_conn_total 146886
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319011
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
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8795
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8571
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 307313
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 5431771944 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 164610674700 (153.31 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 18
```