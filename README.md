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

# Server Metrics 2026-03-18 00:25:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 106841.3 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258840
telemt_connections_bad_total 9525
telemt_handshake_timeouts_total 32426
telemt_upstream_connect_attempt_total 23914
telemt_upstream_connect_success_total 23416
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 23914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32936
telemt_me_reconnect_success_total 15801
telemt_me_reader_eof_total 17161
telemt_me_idle_close_by_peer_total 17160
telemt_me_route_drop_no_conn_total 555130
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1156833
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7518
telemt_desync_full_logged_total 2201
telemt_desync_suppressed_total 5317
telemt_desync_frames_bucket_total{bucket="1_2"} 2011
telemt_desync_frames_bucket_total{bucket="3_10"} 2850
telemt_desync_frames_bucket_total{bucket="gt_10"} 2657
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16570
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15779
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1151047
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 22699257515 (21.14 GB)
telemt_user_octets_to_client{user="hello"} 413853086651 (385.43 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 107092.7 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1336756
telemt_connections_bad_total 62027
telemt_handshake_timeouts_total 45913
telemt_upstream_connect_attempt_total 466458
telemt_upstream_connect_success_total 464913
telemt_upstream_connect_fail_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 466458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1545
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122094
telemt_me_reconnect_success_total 16666
telemt_me_reader_eof_total 18764
telemt_me_idle_close_by_peer_total 18754
telemt_me_route_drop_no_conn_total 345615
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718221
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3277
telemt_desync_full_logged_total 1088
telemt_desync_suppressed_total 2189
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 1349
telemt_desync_frames_bucket_total{bucket="gt_10"} 1292
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 18210
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16648
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1160570
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 15820188941 (14.73 GB)
telemt_user_octets_to_client{user="hello"} 397716256618 (370.40 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 106868.7 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790831
telemt_connections_bad_total 51215
telemt_handshake_timeouts_total 24003
telemt_upstream_connect_attempt_total 25091
telemt_upstream_connect_success_total 24947
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 25091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40259
telemt_me_reconnect_success_total 19577
telemt_me_reader_eof_total 21327
telemt_me_idle_close_by_peer_total 21320
telemt_me_route_drop_no_conn_total 320054
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2155
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1454
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 832
telemt_desync_frames_bucket_total{bucket="gt_10"} 710
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 20490
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19565
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 913
telemt_user_connections_total{user="hello"} 670267
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 32402839988 (30.18 GB)
telemt_user_octets_to_client{user="hello"} 296932488976 (276.54 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 106928.3 (29h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1277373
telemt_connections_bad_total 52215
telemt_handshake_timeouts_total 21793
telemt_upstream_connect_attempt_total 86237
telemt_upstream_connect_success_total 84820
telemt_upstream_connect_fail_total 1417
telemt_upstream_connect_attempts_per_request{bucket="1"} 86237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1417
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35840
telemt_me_reconnect_success_total 15480
telemt_me_reader_eof_total 17084
telemt_me_idle_close_by_peer_total 17082
telemt_me_route_drop_no_conn_total 523430
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1039979
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3916
telemt_desync_full_logged_total 1295
telemt_desync_suppressed_total 2621
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 1648
telemt_desync_frames_bucket_total{bucket="gt_10"} 1314
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 16408
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15470
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 928
telemt_user_connections_total{user="hello"} 1103104
telemt_user_connections_current{user="hello"} 539
telemt_user_octets_from_client{user="hello"} 17317735967 (16.13 GB)
telemt_user_octets_to_client{user="hello"} 513119775646 (477.88 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 106900.0 (29h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835053
telemt_connections_bad_total 98801
telemt_handshake_timeouts_total 6741
telemt_upstream_connect_attempt_total 44144
telemt_upstream_connect_success_total 43535
telemt_upstream_connect_fail_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 44144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 411
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 609
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56681
telemt_me_reconnect_success_total 21723
telemt_me_reader_eof_total 23611
telemt_me_idle_close_by_peer_total 23609
telemt_me_route_drop_no_conn_total 264523
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671270
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3178
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1272
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23171
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21715
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1448
telemt_user_connections_total{user="hello"} 687878
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 13520762324 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 346674397744 (322.87 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 107061.0 (29h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1073000
telemt_connections_bad_total 102008
telemt_handshake_timeouts_total 9595
telemt_upstream_connect_attempt_total 21248
telemt_upstream_connect_success_total 21130
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27090
telemt_me_reconnect_success_total 15808
telemt_me_reader_eof_total 17155
telemt_me_idle_close_by_peer_total 17153
telemt_me_route_drop_no_conn_total 719771
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1036795
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 93
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16415
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15794
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 607
telemt_user_connections_total{user="hello"} 892622
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 14337227708 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 377900383704 (351.95 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 54828.2 (15h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 389973
telemt_connections_bad_total 44675
telemt_handshake_timeouts_total 10822
telemt_upstream_connect_attempt_total 20602
telemt_upstream_connect_success_total 20416
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 20602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29132
telemt_me_reconnect_success_total 17533
telemt_me_reader_eof_total 18543
telemt_me_idle_close_by_peer_total 18543
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 97633
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288655
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1093
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 749
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 411
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18095
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17502
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 288596
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 22130862413 (20.61 GB)
telemt_user_octets_to_client{user="hello"} 238076876278 (221.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 31
```