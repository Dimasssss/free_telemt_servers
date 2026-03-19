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

# Server Metrics 2026-03-19 07:04:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 33374.8 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560687
telemt_connections_bad_total 59286
telemt_connections_current 1394
telemt_connections_me_current 1394
telemt_handshake_timeouts_total 23148
telemt_upstream_connect_attempt_total 6419
telemt_upstream_connect_success_total 6305
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 6419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5796
telemt_me_reconnect_success_total 4649
telemt_me_reader_eof_total 4934
telemt_me_idle_close_by_peer_total 4933
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 155061
telemt_me_route_drop_channel_closed_total 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418900
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2670
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1899
telemt_desync_frames_bucket_total{bucket="1_2"} 922
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4736
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4632
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 416037
telemt_user_connections_current{user="hello"} 1394
telemt_user_octets_from_client{user="hello"} 5740534276 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 140614155160 (130.96 GB)
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 33378.5 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1257202
telemt_connections_bad_total 66470
telemt_connections_current 4131
telemt_connections_me_current 4131
telemt_handshake_timeouts_total 30960
telemt_upstream_connect_attempt_total 6232
telemt_upstream_connect_success_total 6113
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 6231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_reconnect_attempts_total 5578
telemt_me_reconnect_success_total 4425
telemt_me_reader_eof_total 4697
telemt_me_idle_close_by_peer_total 4697
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 528327
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043969
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4585
telemt_desync_full_logged_total 1560
telemt_desync_suppressed_total 3025
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1709
telemt_desync_frames_bucket_total{bucket="gt_10"} 2018
telemt_pool_swap_total 28
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4542
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4404
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 1043901
telemt_user_connections_current{user="hello"} 4131
telemt_user_octets_from_client{user="hello"} 20611022116 (19.20 GB)
telemt_user_octets_to_client{user="hello"} 434070602304 (404.26 GB)
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 942
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 33428.6 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106422
telemt_connections_bad_total 89309
telemt_connections_current 2915
telemt_connections_me_current 2915
telemt_handshake_timeouts_total 28007
telemt_upstream_connect_attempt_total 5876
telemt_upstream_connect_success_total 5876
telemt_upstream_connect_attempts_per_request{bucket="1"} 5876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5219
telemt_me_reconnect_success_total 4160
telemt_me_reader_eof_total 4420
telemt_me_idle_close_by_peer_total 4419
telemt_me_route_drop_no_conn_total 396538
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771583
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2945
telemt_desync_full_logged_total 1037
telemt_desync_suppressed_total 1908
telemt_desync_frames_bucket_total{bucket="1_2"} 543
telemt_desync_frames_bucket_total{bucket="3_10"} 1171
telemt_desync_frames_bucket_total{bucket="gt_10"} 1231
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4252
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4136
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 770448
telemt_user_connections_current{user="hello"} 2915
telemt_user_octets_from_client{user="hello"} 11409037720 (10.63 GB)
telemt_user_octets_to_client{user="hello"} 280429882516 (261.17 GB)
telemt_user_unique_ips_current{user="hello"} 937
telemt_user_unique_ips_recent_window{user="hello"} 524
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 33372.2 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1373106
telemt_connections_bad_total 390173
telemt_connections_current 3258
telemt_connections_me_current 3258
telemt_handshake_timeouts_total 31045
telemt_upstream_connect_attempt_total 5848
telemt_upstream_connect_success_total 5811
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4171
telemt_me_reconnect_success_total 4142
telemt_me_reader_eof_total 4388
telemt_me_idle_close_by_peer_total 4388
telemt_me_route_drop_no_conn_total 336937
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817175
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4077
telemt_desync_full_logged_total 1281
telemt_desync_suppressed_total 2796
telemt_desync_frames_bucket_total{bucket="1_2"} 923
telemt_desync_frames_bucket_total{bucket="3_10"} 1822
telemt_desync_frames_bucket_total{bucket="gt_10"} 1332
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 4193
telemt_me_writer_restored_same_endpoint_total 4118
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 816948
telemt_user_connections_current{user="hello"} 3258
telemt_user_octets_from_client{user="hello"} 18400443560 (17.14 GB)
telemt_user_octets_to_client{user="hello"} 415311092300 (386.79 GB)
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 632
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 33384.3 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228141
telemt_connections_bad_total 12387
telemt_connections_current 849
telemt_connections_me_current 849
telemt_handshake_timeouts_total 2017
telemt_upstream_connect_attempt_total 8843
telemt_upstream_connect_success_total 8613
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 8843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 11377
telemt_me_reconnect_success_total 6932
telemt_me_reader_eof_total 7334
telemt_me_idle_close_by_peer_total 7334
telemt_me_route_drop_no_conn_total 104682
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201755
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7110
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6902
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 201739
telemt_user_connections_current{user="hello"} 849
telemt_user_octets_from_client{user="hello"} 3164711524 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 104469370216 (97.29 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 33374.8 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857027
telemt_connections_bad_total 88498
telemt_connections_current 3153
telemt_connections_me_current 3153
telemt_handshake_timeouts_total 36639
telemt_upstream_connect_attempt_total 6790
telemt_upstream_connect_success_total 6790
telemt_upstream_connect_attempts_per_request{bucket="1"} 6790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 5171
telemt_me_reconnect_success_total 5120
telemt_me_reader_eof_total 5391
telemt_me_idle_close_by_peer_total 5391
telemt_me_route_drop_no_conn_total 339365
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699819
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3921
telemt_desync_full_logged_total 1365
telemt_desync_suppressed_total 2556
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 1500
telemt_desync_frames_bucket_total{bucket="gt_10"} 1638
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5176
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 5105
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 699587
telemt_user_connections_current{user="hello"} 3153
telemt_user_octets_from_client{user="hello"} 10416042708 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 396057992372 (368.86 GB)
telemt_user_unique_ips_current{user="hello"} 960
telemt_user_unique_ips_recent_window{user="hello"} 510
```