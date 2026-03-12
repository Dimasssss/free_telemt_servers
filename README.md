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

# Server Metrics 2026-03-12 18:26:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 39165.4 (10h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200399
telemt_connections_bad_total 2415
telemt_handshake_timeouts_total 4952
telemt_upstream_connect_attempt_total 9959
telemt_upstream_connect_success_total 9916
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5481
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 11351
telemt_me_reconnect_success_total 7894
telemt_me_reader_eof_total 8357
telemt_me_idle_close_by_peer_total 8356
telemt_me_route_drop_no_conn_total 59786
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168978
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8096
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7878
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 168937
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 2995852968 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 71242675864 (66.35 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 39058.2 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86955
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 18009
telemt_upstream_connect_success_total 17756
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 18009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 41630
telemt_me_reconnect_success_total 9079
telemt_me_reader_eof_total 10268
telemt_me_idle_close_by_peer_total 10268
telemt_me_route_drop_no_conn_total 35281
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10168
telemt_me_refill_failed_total 1016
telemt_me_writer_restored_same_endpoint_total 9064
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1089
telemt_user_connections_total{user="hello"} 82703
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 887682009 (846.56 MB)
telemt_user_octets_to_client{user="hello"} 22986418954 (21.41 GB)
telemt_user_msgs_from_client{user="hello"} 101985
telemt_user_msgs_to_client{user="hello"} 700383
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 39021.7 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113468
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2114
telemt_upstream_connect_attempt_total 10942
telemt_upstream_connect_success_total 10942
telemt_upstream_connect_attempts_per_request{bucket="1"} 10942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 10030
telemt_me_reconnect_success_total 8900
telemt_me_reader_eof_total 9431
telemt_me_idle_close_by_peer_total 9431
telemt_me_route_drop_no_conn_total 42507
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105214
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9019
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 8880
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 105187
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2419278372 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 53974760312 (50.27 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38997.5 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163051
telemt_connections_bad_total 13101
telemt_handshake_timeouts_total 1177
telemt_upstream_connect_attempt_total 17618
telemt_upstream_connect_success_total 8806
telemt_upstream_connect_fail_total 8571
telemt_upstream_connect_attempts_per_request{bucket="1"} 17377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8571
telemt_me_keepalive_timeout_total 2406
telemt_me_reconnect_attempts_total 37461
telemt_me_reconnect_success_total 6687
telemt_me_reader_eof_total 7843
telemt_me_idle_close_by_peer_total 7836
telemt_me_route_drop_no_conn_total 56457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132468
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7777
telemt_me_refill_failed_total 959
telemt_me_writer_restored_same_endpoint_total 6679
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 18261
telemt_me_writer_removed_unexpected_minus_restored_total 1090
telemt_user_connections_total{user="hello"} 132521
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2352902480 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 54088702779 (50.37 GB)
telemt_user_msgs_from_client{user="hello"} 633
telemt_user_msgs_to_client{user="hello"} 832
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38966.8 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99631
telemt_connections_bad_total 9993
telemt_handshake_timeouts_total 1329
telemt_upstream_connect_attempt_total 53692
telemt_upstream_connect_success_total 53217
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 53692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 54770
telemt_me_reconnect_success_total 3756
telemt_me_reader_eof_total 5347
telemt_me_idle_close_by_peer_total 5347
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 14149
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36426
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 451
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5376
telemt_me_refill_failed_total 1597
telemt_me_writer_restored_same_endpoint_total 3739
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1620
telemt_user_connections_total{user="hello"} 83891
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 744285432 (709.81 MB)
telemt_user_octets_to_client{user="hello"} 24539516491 (22.85 GB)
telemt_user_msgs_from_client{user="hello"} 725405
telemt_user_msgs_to_client{user="hello"} 2774823
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38954.8 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248747
telemt_connections_bad_total 1575
telemt_handshake_timeouts_total 2099
telemt_upstream_connect_attempt_total 8307
telemt_upstream_connect_success_total 8264
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 8307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 466
telemt_me_reconnect_attempts_total 9873
telemt_me_reconnect_success_total 6270
telemt_me_reader_eof_total 6683
telemt_me_idle_close_by_peer_total 6682
telemt_me_route_drop_no_conn_total 114361
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247133
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6463
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6263
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 237059
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 4157588976 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 108996082248 (101.51 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 47
```