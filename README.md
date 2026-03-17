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

# Server Metrics 2026-03-17 23:24:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 103177.1 (28h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1233660
telemt_connections_bad_total 9042
telemt_handshake_timeouts_total 32274
telemt_upstream_connect_attempt_total 23219
telemt_upstream_connect_success_total 22724
telemt_upstream_connect_fail_total 495
telemt_upstream_connect_attempts_per_request{bucket="1"} 23219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 495
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32416
telemt_me_reconnect_success_total 15283
telemt_me_reader_eof_total 16599
telemt_me_idle_close_by_peer_total 16598
telemt_me_route_drop_no_conn_total 546947
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132839
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7461
telemt_desync_full_logged_total 2171
telemt_desync_suppressed_total 5290
telemt_desync_frames_bucket_total{bucket="1_2"} 1996
telemt_desync_frames_bucket_total{bucket="3_10"} 2825
telemt_desync_frames_bucket_total{bucket="gt_10"} 2640
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 16040
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15261
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 757
telemt_user_connections_total{user="hello"} 1127062
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 21777942767 (20.28 GB)
telemt_user_octets_to_client{user="hello"} 407238164727 (379.27 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 103428.8 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1305446
telemt_connections_bad_total 60890
telemt_handshake_timeouts_total 45269
telemt_upstream_connect_attempt_total 458737
telemt_upstream_connect_success_total 457828
telemt_upstream_connect_fail_total 909
telemt_upstream_connect_attempts_per_request{bucket="1"} 458737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 909
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58838
telemt_me_reconnect_success_total 15680
telemt_me_reader_eof_total 17713
telemt_me_idle_close_by_peer_total 17713
telemt_me_route_drop_no_conn_total 339419
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 696767
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3193
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 626
telemt_desync_frames_bucket_total{bucket="3_10"} 1306
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 17221
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15664
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 1133196
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 15583289330 (14.51 GB)
telemt_user_octets_to_client{user="hello"} 388787512894 (362.09 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 103204.8 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768300
telemt_connections_bad_total 48383
telemt_handshake_timeouts_total 23712
telemt_upstream_connect_attempt_total 24336
telemt_upstream_connect_success_total 24196
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 24336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39680
telemt_me_reconnect_success_total 18999
telemt_me_reader_eof_total 20707
telemt_me_idle_close_by_peer_total 20700
telemt_me_route_drop_no_conn_total 313984
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653224
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2130
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 701
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19904
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18987
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 905
telemt_user_connections_total{user="hello"} 651477
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 31684288744 (29.51 GB)
telemt_user_octets_to_client{user="hello"} 288273015320 (268.48 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 103264.2 (28h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1256460
telemt_connections_bad_total 47237
telemt_handshake_timeouts_total 21641
telemt_upstream_connect_attempt_total 83933
telemt_upstream_connect_success_total 83496
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 83933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35300
telemt_me_reconnect_success_total 14973
telemt_me_reader_eof_total 16489
telemt_me_idle_close_by_peer_total 16487
telemt_me_route_drop_no_conn_total 517477
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026458
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3868
telemt_desync_full_logged_total 1272
telemt_desync_suppressed_total 2596
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 1621
telemt_desync_frames_bucket_total{bucket="gt_10"} 1301
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15885
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14964
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 912
telemt_user_connections_total{user="hello"} 1088942
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 17145989751 (15.97 GB)
telemt_user_octets_to_client{user="hello"} 495177116673 (461.17 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 103236.1 (28h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 813212
telemt_connections_bad_total 96062
telemt_handshake_timeouts_total 6475
telemt_upstream_connect_attempt_total 43153
telemt_upstream_connect_success_total 42567
telemt_upstream_connect_fail_total 586
telemt_upstream_connect_attempts_per_request{bucket="1"} 43153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 405
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 586
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 55885
telemt_me_reconnect_success_total 20931
telemt_me_reader_eof_total 22788
telemt_me_idle_close_by_peer_total 22786
telemt_me_route_drop_no_conn_total 258275
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652974
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3060
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 2160
telemt_desync_frames_bucket_total{bucket="1_2"} 978
telemt_desync_frames_bucket_total{bucket="3_10"} 1224
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22374
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 20923
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1443
telemt_user_connections_total{user="hello"} 669584
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 13276085916 (12.36 GB)
telemt_user_octets_to_client{user="hello"} 331761737964 (308.98 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 103397.1 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046259
telemt_connections_bad_total 92239
telemt_handshake_timeouts_total 9543
telemt_upstream_connect_attempt_total 20456
telemt_upstream_connect_success_total 20341
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26475
telemt_me_reconnect_success_total 15195
telemt_me_reader_eof_total 16494
telemt_me_idle_close_by_peer_total 16492
telemt_me_route_drop_no_conn_total 700798
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015264
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
telemt_pool_swap_total 89
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15796
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15181
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 878290
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 14233020564 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 371173702980 (345.68 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 51164.3 (14h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373211
telemt_connections_bad_total 44601
telemt_handshake_timeouts_total 10695
telemt_upstream_connect_attempt_total 19483
telemt_upstream_connect_success_total 19304
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 19483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28192
telemt_me_reconnect_success_total 16596
telemt_me_reader_eof_total 17544
telemt_me_idle_close_by_peer_total 17544
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 93870
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280432
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1025
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 703
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17151
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16567
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 555
telemt_user_connections_total{user="hello"} 280370
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 21988462049 (20.48 GB)
telemt_user_octets_to_client{user="hello"} 230220535310 (214.41 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 33
```