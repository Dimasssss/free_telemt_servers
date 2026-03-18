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

# Server Metrics 2026-03-18 03:19:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 117229.0 (32h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1342249
telemt_connections_bad_total 10370
telemt_handshake_timeouts_total 33385
telemt_upstream_connect_attempt_total 25941
telemt_upstream_connect_success_total 25431
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 25941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34431
telemt_me_reconnect_success_total 17288
telemt_me_reader_eof_total 18763
telemt_me_idle_close_by_peer_total 18762
telemt_me_route_drop_no_conn_total 577754
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1235841
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7849
telemt_desync_full_logged_total 2331
telemt_desync_suppressed_total 5518
telemt_desync_frames_bucket_total{bucket="1_2"} 2083
telemt_desync_frames_bucket_total{bucket="3_10"} 2996
telemt_desync_frames_bucket_total{bucket="gt_10"} 2770
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 18082
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17266
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 794
telemt_user_connections_total{user="hello"} 1230051
telemt_user_connections_current{user="hello"} 587
telemt_user_octets_from_client{user="hello"} 24831274951 (23.13 GB)
telemt_user_octets_to_client{user="hello"} 437364031075 (407.33 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 117480.3 (32h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1420742
telemt_connections_bad_total 64619
telemt_handshake_timeouts_total 47634
telemt_upstream_connect_attempt_total 469121
telemt_upstream_connect_success_total 467527
telemt_upstream_connect_fail_total 1594
telemt_upstream_connect_attempts_per_request{bucket="1"} 469121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1594
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125474
telemt_me_reconnect_success_total 18751
telemt_me_reader_eof_total 20982
telemt_me_idle_close_by_peer_total 20969
telemt_me_route_drop_no_conn_total 366349
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 794927
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3704
telemt_desync_full_logged_total 1273
telemt_desync_suppressed_total 2431
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 1537
telemt_desync_frames_bucket_total{bucket="gt_10"} 1440
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 20363
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18733
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1612
telemt_user_connections_total{user="hello"} 1237272
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 16594224125 (15.45 GB)
telemt_user_octets_to_client{user="hello"} 437936642858 (407.86 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 117256.4 (32h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 867227
telemt_connections_bad_total 61165
telemt_handshake_timeouts_total 25067
telemt_upstream_connect_attempt_total 27276
telemt_upstream_connect_success_total 27118
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 27276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 41917
telemt_me_reconnect_success_total 21222
telemt_me_reader_eof_total 23084
telemt_me_idle_close_by_peer_total 23077
telemt_me_route_drop_no_conn_total 339109
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 729155
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2296
telemt_desync_full_logged_total 746
telemt_desync_suppressed_total 1550
telemt_desync_frames_bucket_total{bucket="1_2"} 657
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 22153
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21210
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 931
telemt_user_connections_total{user="hello"} 727270
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 44277788964 (41.24 GB)
telemt_user_octets_to_client{user="hello"} 325201833980 (302.87 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 117315.7 (32h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344112
telemt_connections_bad_total 62679
telemt_handshake_timeouts_total 23677
telemt_upstream_connect_attempt_total 90138
telemt_upstream_connect_success_total 87712
telemt_upstream_connect_fail_total 2426
telemt_upstream_connect_attempts_per_request{bucket="1"} 90138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2426
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37499
telemt_me_reconnect_success_total 17094
telemt_me_reader_eof_total 18803
telemt_me_idle_close_by_peer_total 18800
telemt_me_route_drop_no_conn_total 548852
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1090882
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4051
telemt_desync_full_logged_total 1335
telemt_desync_suppressed_total 2716
telemt_desync_frames_bucket_total{bucket="1_2"} 996
telemt_desync_frames_bucket_total{bucket="3_10"} 1687
telemt_desync_frames_bucket_total{bucket="gt_10"} 1368
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 18052
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17074
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 958
telemt_user_connections_total{user="hello"} 1154247
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 17972159786 (16.74 GB)
telemt_user_octets_to_client{user="hello"} 549876673374 (512.11 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 117287.7 (32h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 902764
telemt_connections_bad_total 101424
telemt_handshake_timeouts_total 7147
telemt_upstream_connect_attempt_total 47008
telemt_upstream_connect_success_total 46366
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 47008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 58994
telemt_me_reconnect_success_total 24030
telemt_me_reader_eof_total 26039
telemt_me_idle_close_by_peer_total 26036
telemt_me_route_drop_no_conn_total 288073
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 730558
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3319
telemt_desync_full_logged_total 1002
telemt_desync_suppressed_total 2317
telemt_desync_frames_bucket_total{bucket="1_2"} 1029
telemt_desync_frames_bucket_total{bucket="3_10"} 1324
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25500
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24022
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1470
telemt_user_connections_total{user="hello"} 747075
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 14302033592 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 368005782384 (342.73 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 117448.5 (32h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1146555
telemt_connections_bad_total 126838
telemt_handshake_timeouts_total 10139
telemt_upstream_connect_attempt_total 23394
telemt_upstream_connect_success_total 23258
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 23394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28702
telemt_me_reconnect_success_total 17411
telemt_me_reader_eof_total 18878
telemt_me_idle_close_by_peer_total 18876
telemt_me_route_drop_no_conn_total 792178
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1122599
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2129
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 468
telemt_desync_frames_bucket_total{bucket="3_10"} 809
telemt_desync_frames_bucket_total{bucket="gt_10"} 852
telemt_pool_swap_total 105
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18036
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17397
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 938230
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 15038556748 (14.01 GB)
telemt_user_octets_to_client{user="hello"} 411716741528 (383.44 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 65215.8 (18h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449288
telemt_connections_bad_total 45116
telemt_handshake_timeouts_total 11840
telemt_upstream_connect_attempt_total 23750
telemt_upstream_connect_success_total 23511
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 23750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10812
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 31713
telemt_me_reconnect_success_total 20103
telemt_me_reader_eof_total 21244
telemt_me_idle_close_by_peer_total 21244
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 110444
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325571
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1415
telemt_desync_full_logged_total 461
telemt_desync_suppressed_total 954
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 640
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20684
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20061
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 325364
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 22797414605 (21.23 GB)
telemt_user_octets_to_client{user="hello"} 271979832274 (253.30 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 43
```