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

# Server Metrics 2026-03-13 13:23:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 107393.7 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441812
telemt_connections_bad_total 3214
telemt_handshake_timeouts_total 8463
telemt_upstream_connect_attempt_total 27185
telemt_upstream_connect_success_total 27057
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 27185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2404
telemt_me_reconnect_attempts_total 25192
telemt_me_reconnect_success_total 21665
telemt_me_reader_eof_total 23140
telemt_me_idle_close_by_peer_total 23139
telemt_me_route_drop_no_conn_total 141621
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385186
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1298
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 838
telemt_desync_frames_bucket_total{bucket="1_2"} 278
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 22001
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21649
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 384767
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 7023992616 (6.54 GB)
telemt_user_octets_to_client{user="hello"} 168314580652 (156.76 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 107287.6 (29h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205798
telemt_connections_bad_total 1680
telemt_handshake_timeouts_total 1514
telemt_upstream_connect_attempt_total 66052
telemt_upstream_connect_success_total 65327
telemt_upstream_connect_fail_total 725
telemt_upstream_connect_attempts_per_request{bucket="1"} 66052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 628
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 725
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 102066
telemt_me_reconnect_success_total 25992
telemt_me_reader_eof_total 29129
telemt_me_idle_close_by_peer_total 29129
telemt_me_route_drop_no_conn_total 79647
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160552
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
telemt_me_writer_removed_unexpected_total 28593
telemt_me_refill_failed_total 2373
telemt_me_writer_restored_same_endpoint_total 25975
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2601
telemt_user_connections_total{user="hello"} 194290
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 1996829716 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 63470716242 (59.11 GB)
telemt_user_msgs_from_client{user="hello"} 514523
telemt_user_msgs_to_client{user="hello"} 3636227
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 107251.4 (29h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250914
telemt_connections_bad_total 2074
telemt_handshake_timeouts_total 9561
telemt_upstream_connect_attempt_total 28956
telemt_upstream_connect_success_total 28952
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2244
telemt_me_reconnect_attempts_total 24736
telemt_me_reconnect_success_total 23523
telemt_me_reader_eof_total 25201
telemt_me_idle_close_by_peer_total 25201
telemt_me_route_drop_no_conn_total 91761
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230207
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
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 23779
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23503
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 256
telemt_user_connections_total{user="hello"} 230123
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 9438396688 (8.79 GB)
telemt_user_octets_to_client{user="hello"} 99714962304 (92.87 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 107226.9 (29h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347955
telemt_connections_bad_total 15025
telemt_handshake_timeouts_total 3410
telemt_upstream_connect_attempt_total 40864
telemt_upstream_connect_success_total 30754
telemt_upstream_connect_fail_total 10110
telemt_upstream_connect_attempts_per_request{bucket="1"} 40864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10110
telemt_me_keepalive_timeout_total 4123
telemt_me_reconnect_attempts_total 93880
telemt_me_reconnect_success_total 22326
telemt_me_reader_eof_total 25234
telemt_me_idle_close_by_peer_total 25227
telemt_me_route_drop_no_conn_total 124671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299427
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1098
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 413
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 24844
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 22316
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2518
telemt_user_connections_total{user="hello"} 302338
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 6492110922 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 113448439573 (105.66 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 57398.4 (15h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85296
telemt_connections_bad_total 11335
telemt_handshake_timeouts_total 1194
telemt_upstream_connect_attempt_total 24246
telemt_upstream_connect_success_total 24051
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 24246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 994
telemt_me_reconnect_attempts_total 26189
telemt_me_reconnect_success_total 16270
telemt_me_reader_eof_total 17463
telemt_me_idle_close_by_peer_total 17463
telemt_me_route_drop_no_conn_total 25450
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65147
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 178
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 16720
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16252
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 70047
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 859053365 (819.26 MB)
telemt_user_octets_to_client{user="hello"} 20012525843 (18.64 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 107183.3 (29h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621796
telemt_connections_bad_total 17929
telemt_handshake_timeouts_total 17039
telemt_upstream_connect_attempt_total 22669
telemt_upstream_connect_success_total 22553
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 22669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 2504
telemt_me_reconnect_attempts_total 21831
telemt_me_reconnect_success_total 17208
telemt_me_reader_eof_total 18472
telemt_me_idle_close_by_peer_total 18469
telemt_me_route_drop_no_conn_total 303336
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 592648
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 472
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17576
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17201
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 565693
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 9882660324 (9.20 GB)
telemt_user_octets_to_client{user="hello"} 300973705488 (280.30 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 55
```