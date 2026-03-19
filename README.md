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

# Server Metrics 2026-03-19 10:24:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 45341.8 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008738
telemt_connections_bad_total 88578
telemt_connections_current 1433
telemt_connections_me_current 1433
telemt_handshake_timeouts_total 36486
telemt_upstream_connect_attempt_total 8624
telemt_upstream_connect_success_total 8472
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 8624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 7346
telemt_me_reconnect_success_total 6186
telemt_me_reader_eof_total 6560
telemt_me_idle_close_by_peer_total 6559
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 343361
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774670
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4580
telemt_desync_full_logged_total 1402
telemt_desync_suppressed_total 3178
telemt_desync_frames_bucket_total{bucket="1_2"} 1525
telemt_desync_frames_bucket_total{bucket="3_10"} 1668
telemt_desync_frames_bucket_total{bucket="gt_10"} 1387
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6298
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6166
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 769028
telemt_user_connections_current{user="hello"} 1433
telemt_user_octets_from_client{user="hello"} 11989676548 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 245446498972 (228.59 GB)
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 45346.9 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2501203
telemt_connections_bad_total 157862
telemt_connections_current 4422
telemt_connections_me_current 4422
telemt_handshake_timeouts_total 54301
telemt_upstream_connect_attempt_total 8657
telemt_upstream_connect_success_total 8497
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 8657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8544
telemt_me_reconnect_success_total 6190
telemt_me_reader_eof_total 6578
telemt_me_idle_close_by_peer_total 6578
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1147459
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2070754
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9502
telemt_desync_full_logged_total 3150
telemt_desync_suppressed_total 6352
telemt_desync_frames_bucket_total{bucket="1_2"} 1751
telemt_desync_frames_bucket_total{bucket="3_10"} 3742
telemt_desync_frames_bucket_total{bucket="gt_10"} 4009
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6376
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6168
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2070420
telemt_user_connections_current{user="hello"} 4422
telemt_user_octets_from_client{user="hello"} 32249730560 (30.03 GB)
telemt_user_octets_to_client{user="hello"} 744478798392 (693.35 GB)
telemt_user_unique_ips_current{user="hello"} 1521
telemt_user_unique_ips_recent_window{user="hello"} 754
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 45343.9 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2159398
telemt_connections_bad_total 254712
telemt_connections_current 2876
telemt_connections_me_current 2876
telemt_handshake_timeouts_total 48112
telemt_upstream_connect_attempt_total 8109
telemt_upstream_connect_success_total 8109
telemt_upstream_connect_attempts_per_request{bucket="1"} 8109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5838
telemt_me_reconnect_success_total 5802
telemt_me_reader_eof_total 6143
telemt_me_idle_close_by_peer_total 6143
telemt_me_route_drop_no_conn_total 1328292
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1694108
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7251
telemt_desync_full_logged_total 2322
telemt_desync_suppressed_total 4929
telemt_desync_frames_bucket_total{bucket="1_2"} 1605
telemt_desync_frames_bucket_total{bucket="3_10"} 2683
telemt_desync_frames_bucket_total{bucket="gt_10"} 2963
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5905
telemt_me_writer_restored_same_endpoint_total 5786
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 1692486
telemt_user_connections_current{user="hello"} 2876
telemt_user_octets_from_client{user="hello"} 24396862120 (22.72 GB)
telemt_user_octets_to_client{user="hello"} 735036001752 (684.56 GB)
telemt_user_unique_ips_current{user="hello"} 989
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 45396.8 (12h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2137280
telemt_connections_bad_total 119121
telemt_connections_current 2921
telemt_connections_me_current 2921
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 55798
telemt_upstream_connect_attempt_total 16384
telemt_upstream_connect_success_total 16232
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 16384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9085
telemt_me_reconnect_success_total 5766
telemt_me_reader_eof_total 6130
telemt_me_idle_close_by_peer_total 6129
telemt_me_route_drop_no_conn_total 1088756
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1619970
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5880
telemt_desync_full_logged_total 2003
telemt_desync_suppressed_total 3877
telemt_desync_frames_bucket_total{bucket="1_2"} 1221
telemt_desync_frames_bucket_total{bucket="3_10"} 2290
telemt_desync_frames_bucket_total{bucket="gt_10"} 2369
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6184
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5742
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 1626193
telemt_user_connections_current{user="hello"} 2921
telemt_user_octets_from_client{user="hello"} 18797522268 (17.51 GB)
telemt_user_octets_to_client{user="hello"} 468855626366 (436.66 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 45340.2 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2535098
telemt_connections_bad_total 571188
telemt_connections_current 3465
telemt_connections_me_current 3465
telemt_handshake_timeouts_total 51353
telemt_upstream_connect_attempt_total 7998
telemt_upstream_connect_success_total 7942
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6846
telemt_me_reconnect_success_total 5647
telemt_me_reader_eof_total 6009
telemt_me_idle_close_by_peer_total 6008
telemt_me_route_drop_no_conn_total 943955
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1669334
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7461
telemt_desync_full_logged_total 2320
telemt_desync_suppressed_total 5141
telemt_desync_frames_bucket_total{bucket="1_2"} 1503
telemt_desync_frames_bucket_total{bucket="3_10"} 3231
telemt_desync_frames_bucket_total{bucket="gt_10"} 2727
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 5766
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5623
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 1668446
telemt_user_connections_current{user="hello"} 3465
telemt_user_octets_from_client{user="hello"} 29412794504 (27.39 GB)
telemt_user_octets_to_client{user="hello"} 697842030180 (649.92 GB)
telemt_user_unique_ips_current{user="hello"} 1163
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 45352.5 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446891
telemt_connections_bad_total 18282
telemt_connections_current 910
telemt_connections_me_current 910
telemt_handshake_timeouts_total 3520
telemt_upstream_connect_attempt_total 11393
telemt_upstream_connect_success_total 11104
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 11393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14199
telemt_me_reconnect_success_total 8809
telemt_me_reader_eof_total 9345
telemt_me_idle_close_by_peer_total 9345
telemt_me_route_drop_no_conn_total 228308
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 402706
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 761
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 294
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9052
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8779
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 402669
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 6445294712 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 155517053908 (144.84 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 45342.8 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1699517
telemt_connections_bad_total 136697
telemt_connections_current 3070
telemt_connections_me_current 3070
telemt_handshake_timeouts_total 68968
telemt_upstream_connect_attempt_total 9205
telemt_upstream_connect_success_total 9204
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8252
telemt_me_reconnect_success_total 6898
telemt_me_reader_eof_total 7300
telemt_me_idle_close_by_peer_total 7299
telemt_me_route_drop_no_conn_total 673514
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1419672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8057
telemt_desync_full_logged_total 2610
telemt_desync_suppressed_total 5447
telemt_desync_frames_bucket_total{bucket="1_2"} 1512
telemt_desync_frames_bucket_total{bucket="3_10"} 3032
telemt_desync_frames_bucket_total{bucket="gt_10"} 3513
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7024
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6883
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 1418478
telemt_user_connections_current{user="hello"} 3070
telemt_user_octets_from_client{user="hello"} 19827406172 (18.47 GB)
telemt_user_octets_to_client{user="hello"} 681463896036 (634.66 GB)
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 407
```