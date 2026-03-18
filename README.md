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

# Server Metrics 2026-03-18 03:24:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 117534.5 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344615
telemt_connections_bad_total 10386
telemt_handshake_timeouts_total 33425
telemt_upstream_connect_attempt_total 25994
telemt_upstream_connect_success_total 25484
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 25994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12219
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34484
telemt_me_reconnect_success_total 17341
telemt_me_reader_eof_total 18816
telemt_me_idle_close_by_peer_total 18815
telemt_me_route_drop_no_conn_total 578530
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1238074
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7859
telemt_desync_full_logged_total 2333
telemt_desync_suppressed_total 5526
telemt_desync_frames_bucket_total{bucket="1_2"} 2083
telemt_desync_frames_bucket_total{bucket="3_10"} 3002
telemt_desync_frames_bucket_total{bucket="gt_10"} 2774
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 18135
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17319
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 794
telemt_user_connections_total{user="hello"} 1232281
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 24848519867 (23.14 GB)
telemt_user_octets_to_client{user="hello"} 438046691223 (407.96 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 117785.9 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1424401
telemt_connections_bad_total 64623
telemt_handshake_timeouts_total 47681
telemt_upstream_connect_attempt_total 469154
telemt_upstream_connect_success_total 467560
telemt_upstream_connect_fail_total 1594
telemt_upstream_connect_attempts_per_request{bucket="1"} 469154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1594
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125507
telemt_me_reconnect_success_total 18784
telemt_me_reader_eof_total 21016
telemt_me_idle_close_by_peer_total 21003
telemt_me_route_drop_no_conn_total 367418
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798175
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3711
telemt_desync_full_logged_total 1275
telemt_desync_suppressed_total 2436
telemt_desync_frames_bucket_total{bucket="1_2"} 728
telemt_desync_frames_bucket_total{bucket="3_10"} 1538
telemt_desync_frames_bucket_total{bucket="gt_10"} 1445
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 20397
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18766
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1613
telemt_user_connections_total{user="hello"} 1240509
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 16635192257 (15.49 GB)
telemt_user_octets_to_client{user="hello"} 439587951986 (409.40 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 117561.9 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 869972
telemt_connections_bad_total 61281
telemt_handshake_timeouts_total 25086
telemt_upstream_connect_attempt_total 27318
telemt_upstream_connect_success_total 27160
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 27318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41959
telemt_me_reconnect_success_total 21263
telemt_me_reader_eof_total 23126
telemt_me_idle_close_by_peer_total 23119
telemt_me_route_drop_no_conn_total 340001
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731610
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2301
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 1553
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 754
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 22195
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21251
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 729725
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 44313435424 (41.27 GB)
telemt_user_octets_to_client{user="hello"} 326865588880 (304.42 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 117621.1 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1346788
telemt_connections_bad_total 62973
telemt_handshake_timeouts_total 23711
telemt_upstream_connect_attempt_total 90184
telemt_upstream_connect_success_total 87758
telemt_upstream_connect_fail_total 2426
telemt_upstream_connect_attempts_per_request{bucket="1"} 90184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2426
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37545
telemt_me_reconnect_success_total 17140
telemt_me_reader_eof_total 18850
telemt_me_idle_close_by_peer_total 18847
telemt_me_route_drop_no_conn_total 549640
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1093141
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4063
telemt_desync_full_logged_total 1340
telemt_desync_suppressed_total 2723
telemt_desync_frames_bucket_total{bucket="1_2"} 996
telemt_desync_frames_bucket_total{bucket="3_10"} 1697
telemt_desync_frames_bucket_total{bucket="gt_10"} 1370
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18099
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17120
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 1156506
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 17998862754 (16.76 GB)
telemt_user_octets_to_client{user="hello"} 551498604694 (513.62 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 117593.2 (32h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 905413
telemt_connections_bad_total 101481
telemt_handshake_timeouts_total 7181
telemt_upstream_connect_attempt_total 47050
telemt_upstream_connect_success_total 46408
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 47050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59036
telemt_me_reconnect_success_total 24072
telemt_me_reader_eof_total 26081
telemt_me_idle_close_by_peer_total 26078
telemt_me_route_drop_no_conn_total 289148
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3322
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 2319
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1324
telemt_desync_frames_bucket_total{bucket="gt_10"} 969
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25542
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24064
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 749573
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 14333495388 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 369381508756 (344.01 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 117754.1 (32h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148097
telemt_connections_bad_total 126838
telemt_handshake_timeouts_total 10148
telemt_upstream_connect_attempt_total 23431
telemt_upstream_connect_success_total 23295
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 23431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11983
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28739
telemt_me_reconnect_success_total 17448
telemt_me_reader_eof_total 18915
telemt_me_idle_close_by_peer_total 18913
telemt_me_route_drop_no_conn_total 792848
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1124086
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2130
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 852
telemt_pool_swap_total 105
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18073
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17434
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 939717
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 15049871336 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 411994609444 (383.70 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 65521.3 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451411
telemt_connections_bad_total 45121
telemt_handshake_timeouts_total 11854
telemt_upstream_connect_attempt_total 23838
telemt_upstream_connect_success_total 23599
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 23838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31801
telemt_me_reconnect_success_total 20190
telemt_me_reader_eof_total 21333
telemt_me_idle_close_by_peer_total 21333
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 110965
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327151
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1418
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 955
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20773
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20148
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 326944
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 22816202233 (21.25 GB)
telemt_user_octets_to_client{user="hello"} 272688692934 (253.96 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 45
```