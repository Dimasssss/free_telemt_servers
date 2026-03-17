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

# Server Metrics 2026-03-17 09:53:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 54476.3 (15h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435786
telemt_connections_bad_total 3693
telemt_handshake_timeouts_total 12432
telemt_upstream_connect_attempt_total 13837
telemt_upstream_connect_success_total 13405
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 13837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9921
telemt_me_reconnect_success_total 8394
telemt_me_reader_eof_total 8922
telemt_me_idle_close_by_peer_total 8921
telemt_me_route_drop_no_conn_total 137736
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393475
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3206
telemt_desync_full_logged_total 853
telemt_desync_suppressed_total 2353
telemt_desync_frames_bucket_total{bucket="1_2"} 840
telemt_desync_frames_bucket_total{bucket="3_10"} 1387
telemt_desync_frames_bucket_total{bucket="gt_10"} 979
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8565
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8372
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 395451
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 5672149531 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 156161028931 (145.44 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 54727.7 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237465
telemt_connections_bad_total 2627
telemt_handshake_timeouts_total 13861
telemt_upstream_connect_attempt_total 14172
telemt_upstream_connect_success_total 13976
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 14172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 19983
telemt_me_reconnect_success_total 11275
telemt_me_reader_eof_total 12109
telemt_me_idle_close_by_peer_total 12109
telemt_me_route_drop_no_conn_total 86190
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208984
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 556
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11661
telemt_me_refill_failed_total 271
telemt_me_writer_restored_same_endpoint_total 11259
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 386
telemt_user_connections_total{user="hello"} 208987
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 2551809168 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 80139321172 (74.64 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 54504.2 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145584
telemt_connections_bad_total 7582
telemt_handshake_timeouts_total 10290
telemt_upstream_connect_attempt_total 14524
telemt_upstream_connect_success_total 14448
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12669
telemt_me_reconnect_success_total 11701
telemt_me_reader_eof_total 12502
telemt_me_idle_close_by_peer_total 12502
telemt_me_route_drop_no_conn_total 44088
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118255
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 367
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11888
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11690
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 118176
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 8611118648 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 36852269628 (34.32 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 54563.1 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321480
telemt_connections_bad_total 6192
telemt_handshake_timeouts_total 11075
telemt_upstream_connect_attempt_total 12475
telemt_upstream_connect_success_total 12360
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 12475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10663
telemt_me_reconnect_success_total 9576
telemt_me_reader_eof_total 10169
telemt_me_idle_close_by_peer_total 10169
telemt_me_route_drop_no_conn_total 88962
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259613
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 565
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 348
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9757
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9568
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 259570
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 2953511130 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 103781725989 (96.65 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 54535.0 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179206
telemt_connections_bad_total 49105
telemt_handshake_timeouts_total 2793
telemt_upstream_connect_attempt_total 16610
telemt_upstream_connect_success_total 16395
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 16610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_reconnect_attempts_total 20671
telemt_me_reconnect_success_total 13550
telemt_me_reader_eof_total 14363
telemt_me_idle_close_by_peer_total 14363
telemt_me_route_drop_no_conn_total 46646
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121886
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 13941
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13542
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 391
telemt_user_connections_total{user="hello"} 121912
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 1854705195 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 55312074146 (51.51 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 54696.3 (15h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419042
telemt_connections_bad_total 48385
telemt_handshake_timeouts_total 4305
telemt_upstream_connect_attempt_total 11132
telemt_upstream_connect_success_total 11072
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 11132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12241
telemt_me_reconnect_success_total 8359
telemt_me_reader_eof_total 9028
telemt_me_idle_close_by_peer_total 9028
telemt_me_route_drop_no_conn_total 276971
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 421755
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 607
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 8609
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8345
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 343638
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 4916383656 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 190150685712 (177.09 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 2463.2 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2407
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 951
telemt_upstream_connect_success_total 929
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 682
telemt_me_reconnect_success_total 655
telemt_me_reader_eof_total 653
telemt_me_idle_close_by_peer_total 653
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 775
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2162
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 667
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 2268
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 30123953 (28.73 MB)
telemt_user_octets_to_client{user="hello"} 8847853478 (8.24 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 5
```