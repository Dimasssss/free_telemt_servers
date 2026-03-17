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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 18:44:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 86345.6 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055124
telemt_connections_bad_total 7520
telemt_handshake_timeouts_total 28944
telemt_upstream_connect_attempt_total 20062
telemt_upstream_connect_success_total 19580
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 20062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 30091
telemt_me_reconnect_success_total 12970
telemt_me_reader_eof_total 14123
telemt_me_idle_close_by_peer_total 14122
telemt_me_route_drop_no_conn_total 479519
telemt_me_route_drop_channel_closed_total 139
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 965634
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6362
telemt_desync_full_logged_total 1813
telemt_desync_suppressed_total 4549
telemt_desync_frames_bucket_total{bucket="1_2"} 1750
telemt_desync_frames_bucket_total{bucket="3_10"} 2440
telemt_desync_frames_bucket_total{bucket="gt_10"} 2172
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13691
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12948
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 721
telemt_user_connections_total{user="hello"} 959874
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 14638277475 (13.63 GB)
telemt_user_octets_to_client{user="hello"} 334911029783 (311.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 86597.1 (24h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016062
telemt_connections_bad_total 55833
telemt_handshake_timeouts_total 34319
telemt_upstream_connect_attempt_total 455821
telemt_upstream_connect_success_total 454952
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 455821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43285
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 56740
telemt_me_reconnect_success_total 13591
telemt_me_reader_eof_total 15490
telemt_me_idle_close_by_peer_total 15490
telemt_me_route_drop_no_conn_total 244389
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 434678
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1597
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 15102
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 13575
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1511
telemt_user_connections_total{user="hello"} 871577
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 11732092034 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 228610613846 (212.91 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 86373.7 (23h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521390
telemt_connections_bad_total 19037
telemt_handshake_timeouts_total 21269
telemt_upstream_connect_attempt_total 21264
telemt_upstream_connect_success_total 21146
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37451
telemt_me_reconnect_success_total 16782
telemt_me_reader_eof_total 18347
telemt_me_idle_close_by_peer_total 18340
telemt_me_route_drop_no_conn_total 237107
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455581
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1260
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 883
telemt_desync_frames_bucket_total{bucket="1_2"} 395
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 17653
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16770
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 871
telemt_user_connections_total{user="hello"} 453780
telemt_user_connections_current{user="hello"} 1119
telemt_user_octets_from_client{user="hello"} 26694240648 (24.86 GB)
telemt_user_octets_to_client{user="hello"} 169527802708 (157.89 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 86432.4 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1006897
telemt_connections_bad_total 24609
telemt_handshake_timeouts_total 19534
telemt_upstream_connect_attempt_total 80949
telemt_upstream_connect_success_total 80547
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 80949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33155
telemt_me_reconnect_success_total 12853
telemt_me_reader_eof_total 14189
telemt_me_idle_close_by_peer_total 14188
telemt_me_route_drop_no_conn_total 421066
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 812743
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2613
telemt_desync_full_logged_total 840
telemt_desync_suppressed_total 1773
telemt_desync_frames_bucket_total{bucket="1_2"} 630
telemt_desync_frames_bucket_total{bucket="3_10"} 1143
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13723
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12844
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 870
telemt_user_connections_total{user="hello"} 875816
telemt_user_connections_current{user="hello"} 1521
telemt_user_octets_from_client{user="hello"} 11570249031 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 318039721817 (296.20 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 86404.4 (24h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577039
telemt_connections_bad_total 75528
telemt_handshake_timeouts_total 5077
telemt_upstream_connect_attempt_total 39542
telemt_upstream_connect_success_total 39020
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 39542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50692
telemt_me_reconnect_success_total 18211
telemt_me_reader_eof_total 19862
telemt_me_idle_close_by_peer_total 19860
telemt_me_route_drop_no_conn_total 174299
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 446835
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2004
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1486
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19536
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18203
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 463504
telemt_user_connections_current{user="hello"} 1260
telemt_user_octets_from_client{user="hello"} 8368088116 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 214350514860 (199.63 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 86565.7 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885502
telemt_connections_bad_total 61433
telemt_handshake_timeouts_total 8656
telemt_upstream_connect_attempt_total 17308
telemt_upstream_connect_success_total 17211
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 24121
telemt_me_reconnect_success_total 12849
telemt_me_reader_eof_total 13979
telemt_me_idle_close_by_peer_total 13977
telemt_me_route_drop_no_conn_total 644485
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903091
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1731
telemt_desync_full_logged_total 593
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 414
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 71
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13418
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12835
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 766141
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 11674527440 (10.87 GB)
telemt_user_octets_to_client{user="hello"} 331287717784 (308.54 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34332.6 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198843
telemt_connections_bad_total 20937
telemt_handshake_timeouts_total 5758
telemt_upstream_connect_attempt_total 15321
telemt_upstream_connect_success_total 15186
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 15321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24850
telemt_me_reconnect_success_total 13269
telemt_me_reader_eof_total 14044
telemt_me_idle_close_by_peer_total 14044
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 48235
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158122
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 396
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 285
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 16
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13787
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 13245
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 518
telemt_user_connections_total{user="hello"} 158070
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 13098410681 (12.20 GB)
telemt_user_octets_to_client{user="hello"} 140704809710 (131.04 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 109
```