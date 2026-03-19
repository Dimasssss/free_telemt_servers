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

# Server Metrics 2026-03-19 08:41:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 39194.7 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754968
telemt_connections_bad_total 75827
telemt_connections_current 1587
telemt_connections_me_current 1587
telemt_handshake_timeouts_total 29925
telemt_upstream_connect_attempt_total 7423
telemt_upstream_connect_success_total 7293
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 7423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 6483
telemt_me_reconnect_success_total 5329
telemt_me_reader_eof_total 5656
telemt_me_idle_close_by_peer_total 5655
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 214905
telemt_me_route_drop_channel_closed_total 86
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576757
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3717
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1264
telemt_desync_frames_bucket_total{bucket="3_10"} 1374
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5425
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5311
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 573772
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 8868337912 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 190007407440 (176.96 GB)
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 253
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 39198.9 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1842435
telemt_connections_bad_total 104903
telemt_connections_current 3913
telemt_connections_me_current 3913
telemt_handshake_timeouts_total 42120
telemt_upstream_connect_attempt_total 7390
telemt_upstream_connect_success_total 7254
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 7390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6430
telemt_me_reconnect_success_total 5270
telemt_me_reader_eof_total 5585
telemt_me_idle_close_by_peer_total 5585
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 805520
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525004
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6744
telemt_desync_full_logged_total 2285
telemt_desync_suppressed_total 4459
telemt_desync_frames_bucket_total{bucket="1_2"} 1209
telemt_desync_frames_bucket_total{bucket="3_10"} 2561
telemt_desync_frames_bucket_total{bucket="gt_10"} 2974
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5402
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5248
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 1524776
telemt_user_connections_current{user="hello"} 3913
telemt_user_octets_from_client{user="hello"} 26102088600 (24.31 GB)
telemt_user_octets_to_client{user="hello"} 579433147052 (539.64 GB)
telemt_user_unique_ips_current{user="hello"} 1358
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 39196.4 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557664
telemt_connections_bad_total 198853
telemt_connections_current 3190
telemt_connections_me_current 3190
telemt_handshake_timeouts_total 38892
telemt_upstream_connect_attempt_total 6988
telemt_upstream_connect_success_total 6988
telemt_upstream_connect_attempts_per_request{bucket="1"} 6988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 5037
telemt_me_reconnect_success_total 5007
telemt_me_reader_eof_total 5303
telemt_me_idle_close_by_peer_total 5303
telemt_me_route_drop_no_conn_total 701345
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1196372
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5623
telemt_desync_full_logged_total 1752
telemt_desync_suppressed_total 3871
telemt_desync_frames_bucket_total{bucket="1_2"} 1245
telemt_desync_frames_bucket_total{bucket="3_10"} 2019
telemt_desync_frames_bucket_total{bucket="gt_10"} 2359
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5099
telemt_me_writer_restored_same_endpoint_total 4991
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1195925
telemt_user_connections_current{user="hello"} 3190
telemt_user_octets_from_client{user="hello"} 19710571800 (18.36 GB)
telemt_user_octets_to_client{user="hello"} 583520656196 (543.45 GB)
telemt_user_unique_ips_current{user="hello"} 1097
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 39264.4 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1624409
telemt_connections_bad_total 96500
telemt_connections_current 2933
telemt_connections_me_current 2933
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 41634
telemt_upstream_connect_attempt_total 15225
telemt_upstream_connect_success_total 15127
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 15225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7384
telemt_me_reconnect_success_total 4994
telemt_me_reader_eof_total 5303
telemt_me_idle_close_by_peer_total 5302
telemt_me_route_drop_no_conn_total 722317
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1167275
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4269
telemt_desync_full_logged_total 1458
telemt_desync_suppressed_total 2811
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 1675
telemt_desync_frames_bucket_total{bucket="gt_10"} 1749
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5249
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 4970
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 1174083
telemt_user_connections_current{user="hello"} 2933
telemt_user_octets_from_client{user="hello"} 15058804836 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 366778656734 (341.59 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 39192.6 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1916583
telemt_connections_bad_total 492634
telemt_connections_current 3526
telemt_connections_me_current 3526
telemt_handshake_timeouts_total 40118
telemt_upstream_connect_attempt_total 6720
telemt_upstream_connect_success_total 6673
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 6720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4737
telemt_me_reconnect_success_total 4700
telemt_me_reader_eof_total 4988
telemt_me_idle_close_by_peer_total 4988
telemt_me_route_drop_no_conn_total 512048
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1189228
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5849
telemt_desync_full_logged_total 1812
telemt_desync_suppressed_total 4037
telemt_desync_frames_bucket_total{bucket="1_2"} 1188
telemt_desync_frames_bucket_total{bucket="3_10"} 2619
telemt_desync_frames_bucket_total{bucket="gt_10"} 2042
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4765
telemt_me_writer_restored_same_endpoint_total 4676
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1188800
telemt_user_connections_current{user="hello"} 3526
telemt_user_octets_from_client{user="hello"} 23568899988 (21.95 GB)
telemt_user_octets_to_client{user="hello"} 553408312036 (515.40 GB)
telemt_user_unique_ips_current{user="hello"} 1185
telemt_user_unique_ips_recent_window{user="hello"} 535
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 39204.8 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329463
telemt_connections_bad_total 14743
telemt_connections_current 886
telemt_connections_me_current 886
telemt_handshake_timeouts_total 2831
telemt_upstream_connect_attempt_total 10036
telemt_upstream_connect_success_total 9774
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 10036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13179
telemt_me_reconnect_success_total 7799
telemt_me_reader_eof_total 8274
telemt_me_idle_close_by_peer_total 8274
telemt_me_route_drop_no_conn_total 151321
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 295287
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 421
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 8022
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7769
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 295249
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 4262799140 (3.97 GB)
telemt_user_octets_to_client{user="hello"} 129084306000 (120.22 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 39195.0 (10h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267025
telemt_connections_bad_total 107692
telemt_connections_current 3137
telemt_connections_me_current 3137
telemt_handshake_timeouts_total 55475
telemt_upstream_connect_attempt_total 7892
telemt_upstream_connect_success_total 7891
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7258
telemt_me_reconnect_success_total 5914
telemt_me_reader_eof_total 6276
telemt_me_idle_close_by_peer_total 6275
telemt_me_route_drop_no_conn_total 496803
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1054787
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6255
telemt_desync_full_logged_total 2053
telemt_desync_suppressed_total 4202
telemt_desync_frames_bucket_total{bucket="1_2"} 1180
telemt_desync_frames_bucket_total{bucket="3_10"} 2352
telemt_desync_frames_bucket_total{bucket="gt_10"} 2723
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6023
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5899
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 1053723
telemt_user_connections_current{user="hello"} 3137
telemt_user_octets_from_client{user="hello"} 14697626640 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 531100868824 (494.63 GB)
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 446
```