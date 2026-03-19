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

# Server Metrics 2026-03-19 11:25:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 49035.0 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1168039
telemt_connections_bad_total 98685
telemt_connections_current 1575
telemt_connections_me_current 1575
telemt_handshake_timeouts_total 40757
telemt_upstream_connect_attempt_total 9443
telemt_upstream_connect_success_total 9281
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 9443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 8696
telemt_me_reconnect_success_total 6811
telemt_me_reader_eof_total 7211
telemt_me_idle_close_by_peer_total 7208
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 491509
telemt_me_route_drop_channel_closed_total 181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912201
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5064
telemt_desync_full_logged_total 1543
telemt_desync_suppressed_total 3521
telemt_desync_frames_bucket_total{bucket="1_2"} 1656
telemt_desync_frames_bucket_total{bucket="3_10"} 1838
telemt_desync_frames_bucket_total{bucket="gt_10"} 1570
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6967
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6790
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 906139
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 13877073376 (12.92 GB)
telemt_user_octets_to_client{user="hello"} 277091226476 (258.06 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 49038.9 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3110320
telemt_connections_bad_total 193141
telemt_connections_current 3825
telemt_connections_me_current 3825
telemt_handshake_timeouts_total 59735
telemt_upstream_connect_attempt_total 9312
telemt_upstream_connect_success_total 9142
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 9312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 14093
telemt_me_reconnect_success_total 6644
telemt_me_reader_eof_total 7193
telemt_me_idle_close_by_peer_total 7192
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2182135
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2617028
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10617
telemt_desync_full_logged_total 3555
telemt_desync_suppressed_total 7062
telemt_desync_frames_bucket_total{bucket="1_2"} 2051
telemt_desync_frames_bucket_total{bucket="3_10"} 4178
telemt_desync_frames_bucket_total{bucket="gt_10"} 4388
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6993
telemt_me_refill_failed_total 232
telemt_me_writer_restored_same_endpoint_total 6622
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 2616643
telemt_user_connections_current{user="hello"} 3825
telemt_user_octets_from_client{user="hello"} 35867808564 (33.40 GB)
telemt_user_octets_to_client{user="hello"} 820578928688 (764.22 GB)
telemt_user_unique_ips_current{user="hello"} 1404
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 49036.7 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2470739
telemt_connections_bad_total 291962
telemt_connections_current 3123
telemt_connections_me_current 3123
telemt_handshake_timeouts_total 51317
telemt_upstream_connect_attempt_total 8852
telemt_upstream_connect_success_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 8852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7547
telemt_me_reconnect_success_total 6353
telemt_me_reader_eof_total 6749
telemt_me_idle_close_by_peer_total 6748
telemt_me_route_drop_no_conn_total 1537308
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1941715
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8081
telemt_desync_full_logged_total 2569
telemt_desync_suppressed_total 5512
telemt_desync_frames_bucket_total{bucket="1_2"} 1815
telemt_desync_frames_bucket_total{bucket="3_10"} 2982
telemt_desync_frames_bucket_total{bucket="gt_10"} 3284
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6500
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6337
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 1939523
telemt_user_connections_current{user="hello"} 3123
telemt_user_octets_from_client{user="hello"} 27281956720 (25.41 GB)
telemt_user_octets_to_client{user="hello"} 826331471648 (769.58 GB)
telemt_user_unique_ips_current{user="hello"} 1098
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 49089.4 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2461019
telemt_connections_bad_total 132290
telemt_connections_current 3510
telemt_connections_me_current 3510
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 63225
telemt_upstream_connect_attempt_total 17131
telemt_upstream_connect_success_total 16960
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 17131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10641
telemt_me_reconnect_success_total 6301
telemt_me_reader_eof_total 6717
telemt_me_idle_close_by_peer_total 6716
telemt_me_route_drop_no_conn_total 1347113
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1878780
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6840
telemt_desync_full_logged_total 2304
telemt_desync_suppressed_total 4536
telemt_desync_frames_bucket_total{bucket="1_2"} 1440
telemt_desync_frames_bucket_total{bucket="3_10"} 2680
telemt_desync_frames_bucket_total{bucket="gt_10"} 2720
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6765
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6277
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1884939
telemt_user_connections_current{user="hello"} 3510
telemt_user_octets_from_client{user="hello"} 21902464644 (20.40 GB)
telemt_user_octets_to_client{user="hello"} 533035290598 (496.43 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 628
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 49032.9 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2944395
telemt_connections_bad_total 649082
telemt_connections_current 3513
telemt_connections_me_current 3513
telemt_handshake_timeouts_total 57445
telemt_upstream_connect_attempt_total 8710
telemt_upstream_connect_success_total 8646
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 8710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7371
telemt_me_reconnect_success_total 6166
telemt_me_reader_eof_total 6553
telemt_me_idle_close_by_peer_total 6552
telemt_me_route_drop_no_conn_total 1086197
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1940845
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8493
telemt_desync_full_logged_total 2638
telemt_desync_suppressed_total 5855
telemt_desync_frames_bucket_total{bucket="1_2"} 1618
telemt_desync_frames_bucket_total{bucket="3_10"} 3676
telemt_desync_frames_bucket_total{bucket="gt_10"} 3199
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6295
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6142
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 1939915
telemt_user_connections_current{user="hello"} 3513
telemt_user_octets_from_client{user="hello"} 33714463308 (31.40 GB)
telemt_user_octets_to_client{user="hello"} 783386267140 (729.59 GB)
telemt_user_unique_ips_current{user="hello"} 1231
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 49045.3 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507561
telemt_connections_bad_total 18592
telemt_connections_current 1073
telemt_connections_me_current 1073
telemt_handshake_timeouts_total 3950
telemt_upstream_connect_attempt_total 12241
telemt_upstream_connect_success_total 11932
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 12241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17035
telemt_me_reconnect_success_total 9447
telemt_me_reader_eof_total 10074
telemt_me_idle_close_by_peer_total 10074
telemt_me_route_drop_no_conn_total 262245
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460129
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 637
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 23
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9769
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9416
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 460071
telemt_user_connections_current{user="hello"} 1073
telemt_user_octets_from_client{user="hello"} 7431937564 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 170542275436 (158.83 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 49035.1 (13h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2064139
telemt_connections_bad_total 174249
telemt_connections_current 2927
telemt_connections_me_current 2927
telemt_handshake_timeouts_total 72435
telemt_upstream_connect_attempt_total 9864
telemt_upstream_connect_success_total 9863
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8734
telemt_me_reconnect_success_total 7366
telemt_me_reader_eof_total 7801
telemt_me_idle_close_by_peer_total 7800
telemt_me_route_drop_no_conn_total 1048977
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1720096
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9341
telemt_desync_full_logged_total 3008
telemt_desync_suppressed_total 6333
telemt_desync_frames_bucket_total{bucket="1_2"} 1772
telemt_desync_frames_bucket_total{bucket="3_10"} 3576
telemt_desync_frames_bucket_total{bucket="gt_10"} 3993
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7503
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7351
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 1718795
telemt_user_connections_current{user="hello"} 2927
telemt_user_octets_from_client{user="hello"} 22789361008 (21.22 GB)
telemt_user_octets_to_client{user="hello"} 762696934956 (710.32 GB)
telemt_user_unique_ips_current{user="hello"} 984
telemt_user_unique_ips_recent_window{user="hello"} 439
```