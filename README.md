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

# Server Metrics 2026-03-13 19:19:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 128794.1 (35h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546787
telemt_connections_bad_total 12937
telemt_handshake_timeouts_total 12401
telemt_upstream_connect_attempt_total 32610
telemt_upstream_connect_success_total 32443
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 32610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5043
telemt_me_reconnect_attempts_total 30252
telemt_me_reconnect_success_total 25602
telemt_me_reader_eof_total 27341
telemt_me_idle_close_by_peer_total 27340
telemt_me_route_drop_no_conn_total 179994
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472360
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1517
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 998
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 26034
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25586
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 472302
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 8731333358 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 224462078736 (209.05 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 128687.6 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272902
telemt_connections_bad_total 1958
telemt_handshake_timeouts_total 1869
telemt_upstream_connect_attempt_total 124623
telemt_upstream_connect_success_total 123696
telemt_upstream_connect_fail_total 927
telemt_upstream_connect_attempts_per_request{bucket="1"} 124623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27840
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 927
telemt_me_keepalive_timeout_total 3593
telemt_me_reconnect_attempts_total 133755
telemt_me_reconnect_success_total 26225
telemt_me_reader_eof_total 30325
telemt_me_idle_close_by_peer_total 30325
telemt_me_route_drop_no_conn_total 83272
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167831
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_me_writer_removed_unexpected_total 29828
telemt_me_refill_failed_total 3355
telemt_me_writer_restored_same_endpoint_total 26208
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3603
telemt_user_connections_total{user="hello"} 258683
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2672507194 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 78061941540 (72.70 GB)
telemt_user_msgs_from_client{user="hello"} 1430634
telemt_user_msgs_to_client{user="hello"} 8019191
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 128651.6 (35h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320074
telemt_connections_bad_total 2631
telemt_handshake_timeouts_total 21418
telemt_upstream_connect_attempt_total 34190
telemt_upstream_connect_success_total 34185
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 34190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2769
telemt_me_reconnect_attempts_total 28970
telemt_me_reconnect_success_total 27734
telemt_me_reader_eof_total 29747
telemt_me_idle_close_by_peer_total 29747
telemt_me_route_drop_no_conn_total 114311
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284866
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 28047
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27714
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 284775
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 10437994828 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 119794804632 (111.57 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 128626.7 (35h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424883
telemt_connections_bad_total 15174
telemt_handshake_timeouts_total 3922
telemt_upstream_connect_attempt_total 61895
telemt_upstream_connect_success_total 51621
telemt_upstream_connect_fail_total 10274
telemt_upstream_connect_attempts_per_request{bucket="1"} 61895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10274
telemt_me_keepalive_timeout_total 4718
telemt_me_reconnect_attempts_total 116803
telemt_me_reconnect_success_total 26182
telemt_me_reader_eof_total 29778
telemt_me_idle_close_by_peer_total 29771
telemt_me_route_drop_no_conn_total 146907
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356453
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1426
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 546
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 29348
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 26172
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3166
telemt_user_connections_total{user="hello"} 375332
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 8538629763 (7.95 GB)
telemt_user_octets_to_client{user="hello"} 134510079476 (125.27 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 78798.4 (21h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133032
telemt_connections_bad_total 16220
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 30339
telemt_upstream_connect_success_total 30054
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 30339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 1227
telemt_me_reconnect_attempts_total 34602
telemt_me_reconnect_success_total 21211
telemt_me_reader_eof_total 22740
telemt_me_idle_close_by_peer_total 22740
telemt_me_route_drop_no_conn_total 41629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106146
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 594
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 21826
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 21193
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 111041
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 1274727613 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 39736987983 (37.01 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 128583.0 (35h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788088
telemt_connections_bad_total 24786
telemt_handshake_timeouts_total 24853
telemt_upstream_connect_attempt_total 26545
telemt_upstream_connect_success_total 26405
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 26545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 3045
telemt_me_reconnect_attempts_total 24683
telemt_me_reconnect_success_total 20037
telemt_me_reader_eof_total 21500
telemt_me_idle_close_by_peer_total 21497
telemt_me_route_drop_no_conn_total 374704
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20449
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20030
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 711555
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 12355263060 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 351460356588 (327.32 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 51
```