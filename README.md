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

# Server Metrics 2026-03-19 10:08:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 44424.7 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974073
telemt_connections_bad_total 85665
telemt_connections_current 1574
telemt_connections_me_current 1574
telemt_handshake_timeouts_total 35670
telemt_upstream_connect_attempt_total 8444
telemt_upstream_connect_success_total 8296
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 8444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7213
telemt_me_reconnect_success_total 6053
telemt_me_reader_eof_total 6416
telemt_me_idle_close_by_peer_total 6415
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 330593
telemt_me_route_drop_channel_closed_total 137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748038
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4496
telemt_desync_full_logged_total 1372
telemt_desync_suppressed_total 3124
telemt_desync_frames_bucket_total{bucket="1_2"} 1504
telemt_desync_frames_bucket_total{bucket="3_10"} 1643
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6165
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6033
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 742405
telemt_user_connections_current{user="hello"} 1574
telemt_user_octets_from_client{user="hello"} 11671968052 (10.87 GB)
telemt_user_octets_to_client{user="hello"} 237240475756 (220.95 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 44429.7 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2413057
telemt_connections_bad_total 151699
telemt_connections_current 4139
telemt_connections_me_current 4139
telemt_handshake_timeouts_total 53484
telemt_upstream_connect_attempt_total 8458
telemt_upstream_connect_success_total 8301
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 8458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8392
telemt_me_reconnect_success_total 6039
telemt_me_reader_eof_total 6425
telemt_me_idle_close_by_peer_total 6425
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1091975
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1993454
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9111
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 6084
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 3548
telemt_desync_frames_bucket_total{bucket="gt_10"} 3888
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6223
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6017
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1993165
telemt_user_connections_current{user="hello"} 4140
telemt_user_octets_from_client{user="hello"} 31334591072 (29.18 GB)
telemt_user_octets_to_client{user="hello"} 721550213520 (672.00 GB)
telemt_user_unique_ips_current{user="hello"} 1400
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 44427.2 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2087516
telemt_connections_bad_total 248498
telemt_connections_current 3088
telemt_connections_me_current 3088
telemt_handshake_timeouts_total 47199
telemt_upstream_connect_attempt_total 7956
telemt_upstream_connect_success_total 7956
telemt_upstream_connect_attempts_per_request{bucket="1"} 7956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5729
telemt_me_reconnect_success_total 5693
telemt_me_reader_eof_total 6022
telemt_me_idle_close_by_peer_total 6022
telemt_me_route_drop_no_conn_total 1290894
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1635502
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7027
telemt_desync_full_logged_total 2235
telemt_desync_suppressed_total 4792
telemt_desync_frames_bucket_total{bucket="1_2"} 1562
telemt_desync_frames_bucket_total{bucket="3_10"} 2592
telemt_desync_frames_bucket_total{bucket="gt_10"} 2873
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5792
telemt_me_writer_restored_same_endpoint_total 5677
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 1633958
telemt_user_connections_current{user="hello"} 3088
telemt_user_octets_from_client{user="hello"} 23824440136 (22.19 GB)
telemt_user_octets_to_client{user="hello"} 711699797092 (662.82 GB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 516
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 44479.9 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2069523
telemt_connections_bad_total 115714
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 53661
telemt_upstream_connect_attempt_total 16203
telemt_upstream_connect_success_total 16075
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 16203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8948
telemt_me_reconnect_success_total 5655
telemt_me_reader_eof_total 6031
telemt_me_idle_close_by_peer_total 6030
telemt_me_route_drop_no_conn_total 1056886
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560385
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5717
telemt_desync_full_logged_total 1939
telemt_desync_suppressed_total 3778
telemt_desync_frames_bucket_total{bucket="1_2"} 1185
telemt_desync_frames_bucket_total{bucket="3_10"} 2236
telemt_desync_frames_bucket_total{bucket="gt_10"} 2296
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5966
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5631
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 1567032
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 18202467112 (16.95 GB)
telemt_user_octets_to_client{user="hello"} 453708772470 (422.55 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 44423.4 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2448115
telemt_connections_bad_total 563246
telemt_connections_current 3514
telemt_connections_me_current 3514
telemt_handshake_timeouts_total 50136
telemt_upstream_connect_attempt_total 7811
telemt_upstream_connect_success_total 7757
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3785
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6705
telemt_me_reconnect_success_total 5508
telemt_me_reader_eof_total 5856
telemt_me_idle_close_by_peer_total 5856
telemt_me_route_drop_no_conn_total 902154
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1601232
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7201
telemt_desync_full_logged_total 2249
telemt_desync_suppressed_total 4952
telemt_desync_frames_bucket_total{bucket="1_2"} 1454
telemt_desync_frames_bucket_total{bucket="3_10"} 3129
telemt_desync_frames_bucket_total{bucket="gt_10"} 2618
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5625
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5484
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 1600363
telemt_user_connections_current{user="hello"} 3514
telemt_user_octets_from_client{user="hello"} 28631542664 (26.67 GB)
telemt_user_octets_to_client{user="hello"} 676487711452 (630.03 GB)
telemt_user_unique_ips_current{user="hello"} 1142
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 44435.8 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432903
telemt_connections_bad_total 18247
telemt_connections_current 909
telemt_connections_me_current 909
telemt_handshake_timeouts_total 3416
telemt_upstream_connect_attempt_total 11216
telemt_upstream_connect_success_total 10931
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 11216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14070
telemt_me_reconnect_success_total 8680
telemt_me_reader_eof_total 9214
telemt_me_idle_close_by_peer_total 9214
telemt_me_route_drop_no_conn_total 220588
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389320
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 712
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8921
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8650
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 389288
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 6219605100 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 151831845384 (141.40 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 44425.8 (12h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1640161
telemt_connections_bad_total 134887
telemt_connections_current 3095
telemt_connections_me_current 3095
telemt_handshake_timeouts_total 67767
telemt_upstream_connect_attempt_total 8996
telemt_upstream_connect_success_total 8994
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8088
telemt_me_reconnect_success_total 6733
telemt_me_reader_eof_total 7134
telemt_me_idle_close_by_peer_total 7133
telemt_me_route_drop_no_conn_total 654339
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1369223
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7677
telemt_desync_full_logged_total 2510
telemt_desync_suppressed_total 5167
telemt_desync_frames_bucket_total{bucket="1_2"} 1448
telemt_desync_frames_bucket_total{bucket="3_10"} 2888
telemt_desync_frames_bucket_total{bucket="gt_10"} 3341
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6858
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6718
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1368048
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 18630408016 (17.35 GB)
telemt_user_octets_to_client{user="hello"} 660613686524 (615.24 GB)
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 425
```