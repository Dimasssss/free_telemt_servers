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

# Server Metrics 2026-03-14 05:31:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 165462.0 (45h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 638373
telemt_connections_bad_total 32289
telemt_handshake_timeouts_total 12985
telemt_upstream_connect_attempt_total 42230
telemt_upstream_connect_success_total 42014
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5568
telemt_me_reconnect_attempts_total 38081
telemt_me_reconnect_success_total 33394
telemt_me_reader_eof_total 35697
telemt_me_idle_close_by_peer_total 35696
telemt_me_route_drop_no_conn_total 208206
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1911
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1261
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 800
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 33902
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33374
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 540759
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 15918298438 (14.83 GB)
telemt_user_octets_to_client{user="hello"} 261472689924 (243.52 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 165355.0 (45h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322372
telemt_connections_bad_total 2288
telemt_handshake_timeouts_total 2343
telemt_upstream_connect_attempt_total 148243
telemt_upstream_connect_success_total 147029
telemt_upstream_connect_fail_total 1214
telemt_upstream_connect_attempts_per_request{bucket="1"} 148243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1214
telemt_me_keepalive_timeout_total 3896
telemt_me_reconnect_attempts_total 172299
telemt_me_reconnect_success_total 35487
telemt_me_reader_eof_total 40705
telemt_me_idle_close_by_peer_total 40705
telemt_me_route_drop_no_conn_total 103596
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202241
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 40095
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35470
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4608
telemt_user_connections_total{user="hello"} 305350
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 3176472911 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 99373214967 (92.55 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 165318.5 (45h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 374820
telemt_connections_bad_total 2957
telemt_handshake_timeouts_total 34914
telemt_upstream_connect_attempt_total 43791
telemt_upstream_connect_success_total 43782
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3410
telemt_me_reconnect_attempts_total 36792
telemt_me_reconnect_success_total 35508
telemt_me_reader_eof_total 38176
telemt_me_idle_close_by_peer_total 38176
telemt_me_route_drop_no_conn_total 134718
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323945
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 35939
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35487
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 431
telemt_user_connections_total{user="hello"} 323721
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 12739528952 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 129051469924 (120.19 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 165294.2 (45h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476566
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4430
telemt_upstream_connect_attempt_total 73794
telemt_upstream_connect_success_total 63248
telemt_upstream_connect_fail_total 10546
telemt_upstream_connect_attempts_per_request{bucket="1"} 73794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10546
telemt_me_keepalive_timeout_total 5311
telemt_me_reconnect_attempts_total 142037
telemt_me_reconnect_success_total 35984
telemt_me_reader_eof_total 40428
telemt_me_idle_close_by_peer_total 40420
telemt_me_route_drop_no_conn_total 171252
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 404882
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1717
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 39710
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35974
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3726
telemt_user_connections_total{user="hello"} 423723
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 9232030535 (8.60 GB)
telemt_user_octets_to_client{user="hello"} 166989460824 (155.52 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 115465.7 (32h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188956
telemt_connections_bad_total 27822
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 41325
telemt_upstream_connect_success_total 40939
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 41325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_keepalive_timeout_total 2415
telemt_me_reconnect_attempts_total 43714
telemt_me_reconnect_success_total 30289
telemt_me_reader_eof_total 32430
telemt_me_idle_close_by_peer_total 32430
telemt_me_route_drop_no_conn_total 55891
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149413
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 30982
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30271
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 693
telemt_user_connections_total{user="hello"} 154162
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 2292456477 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 69908562423 (65.11 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 165250.2 (45h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 940307
telemt_connections_bad_total 32164
telemt_handshake_timeouts_total 25800
telemt_upstream_connect_attempt_total 34335
telemt_upstream_connect_success_total 34151
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 34335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18080
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 4606
telemt_me_reconnect_attempts_total 30652
telemt_me_reconnect_success_total 25978
telemt_me_reader_eof_total 27885
telemt_me_idle_close_by_peer_total 27882
telemt_me_route_drop_no_conn_total 444940
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 874590
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 26453
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25971
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 847250
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 14721119400 (13.71 GB)
telemt_user_octets_to_client{user="hello"} 432644956760 (402.93 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 45
```