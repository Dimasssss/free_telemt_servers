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

# Server Metrics 2026-03-17 13:22:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 67041.4 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 660874
telemt_connections_bad_total 5207
telemt_handshake_timeouts_total 20221
telemt_upstream_connect_attempt_total 16603
telemt_upstream_connect_success_total 16151
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 15692
telemt_me_reconnect_success_total 10504
telemt_me_reader_eof_total 11222
telemt_me_idle_close_by_peer_total 11221
telemt_me_route_drop_no_conn_total 220640
telemt_me_route_drop_channel_closed_total 67
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597893
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4404
telemt_desync_full_logged_total 1211
telemt_desync_suppressed_total 3193
telemt_desync_frames_bucket_total{bucket="1_2"} 1262
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10817
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 10482
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 599784
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 8940980747 (8.33 GB)
telemt_user_octets_to_client{user="hello"} 211743302671 (197.20 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 67293.0 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400469
telemt_connections_bad_total 24236
telemt_handshake_timeouts_total 20764
telemt_upstream_connect_attempt_total 16884
telemt_upstream_connect_success_total 16610
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 16884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 27627
telemt_me_reconnect_success_total 13233
telemt_me_reader_eof_total 14258
telemt_me_idle_close_by_peer_total 14258
telemt_me_route_drop_no_conn_total 167975
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1304
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 578
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13845
telemt_me_refill_failed_total 446
telemt_me_writer_restored_same_endpoint_total 13217
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 334745
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 3706174136 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 115243111008 (107.33 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 67068.9 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217157
telemt_connections_bad_total 7758
telemt_handshake_timeouts_total 16634
telemt_upstream_connect_attempt_total 17706
telemt_upstream_connect_success_total 17616
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 17706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 17345
telemt_me_reconnect_success_total 14216
telemt_me_reader_eof_total 15180
telemt_me_idle_close_by_peer_total 15180
telemt_me_route_drop_no_conn_total 76024
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181388
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 709
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14511
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 14205
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 181275
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 15246340344 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 50756096652 (47.27 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 67128.3 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497543
telemt_connections_bad_total 7915
telemt_handshake_timeouts_total 12671
telemt_upstream_connect_attempt_total 16131
telemt_upstream_connect_success_total 15985
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 16131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 16887
telemt_me_reconnect_success_total 11583
telemt_me_reader_eof_total 12409
telemt_me_idle_close_by_peer_total 12409
telemt_me_route_drop_no_conn_total 144506
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420627
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1503
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 981
telemt_desync_frames_bucket_total{bucket="1_2"} 369
telemt_desync_frames_bucket_total{bucket="3_10"} 673
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11952
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 11574
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 421491
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 5360722822 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 144499518419 (134.58 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 67100.4 (18h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249271
telemt_connections_bad_total 56122
telemt_handshake_timeouts_total 3237
telemt_upstream_connect_attempt_total 19384
telemt_upstream_connect_success_total 19133
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 19383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 32863
telemt_me_reconnect_success_total 15646
telemt_me_reader_eof_total 16821
telemt_me_idle_close_by_peer_total 16821
telemt_me_route_drop_no_conn_total 65670
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180758
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1076
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16390
telemt_me_refill_failed_total 535
telemt_me_writer_restored_same_endpoint_total 15638
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 180801
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 2347123743 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 69919293278 (65.12 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 67262.1 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593155
telemt_connections_bad_total 53243
telemt_handshake_timeouts_total 5973
telemt_upstream_connect_attempt_total 13640
telemt_upstream_connect_success_total 13568
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 13640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6834
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 15145
telemt_me_reconnect_success_total 10211
telemt_me_reader_eof_total 11007
telemt_me_idle_close_by_peer_total 11007
telemt_me_route_drop_no_conn_total 396725
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593366
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10523
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 10197
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 503079
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 7311029340 (6.81 GB)
telemt_user_octets_to_client{user="hello"} 238686551672 (222.29 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 15028.3 (4h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11753
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 8488
telemt_upstream_connect_success_total 8417
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 8488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 12832
telemt_me_reconnect_success_total 7499
telemt_me_reader_eof_total 7858
telemt_me_idle_close_by_peer_total 7858
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11355
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 7737
telemt_me_refill_failed_total 165
telemt_me_writer_restored_same_endpoint_total 7485
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 11457
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 325270081 (310.20 MB)
telemt_user_octets_to_client{user="hello"} 21508346638 (20.03 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 14
```