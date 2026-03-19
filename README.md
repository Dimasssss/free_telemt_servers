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

# Server Metrics 2026-03-19 09:43:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 42882.5 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 903848
telemt_connections_bad_total 81955
telemt_connections_current 1682
telemt_connections_me_current 1682
telemt_handshake_timeouts_total 34394
telemt_upstream_connect_attempt_total 8154
telemt_upstream_connect_success_total 8013
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 8154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7022
telemt_me_reconnect_success_total 5864
telemt_me_reader_eof_total 6214
telemt_me_idle_close_by_peer_total 6213
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 304555
telemt_me_route_drop_channel_closed_total 121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700482
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4282
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 2981
telemt_desync_frames_bucket_total{bucket="1_2"} 1436
telemt_desync_frames_bucket_total{bucket="3_10"} 1569
telemt_desync_frames_bucket_total{bucket="gt_10"} 1277
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5972
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5845
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 694911
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 11043711508 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 223707507708 (208.34 GB)
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 249
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 42886.5 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2245790
telemt_connections_bad_total 140574
telemt_connections_current 4253
telemt_connections_me_current 4253
telemt_handshake_timeouts_total 49671
telemt_upstream_connect_attempt_total 8181
telemt_upstream_connect_success_total 8030
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 8181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8210
telemt_me_reconnect_success_total 5862
telemt_me_reader_eof_total 6235
telemt_me_idle_close_by_peer_total 6235
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 981570
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1852105
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8475
telemt_desync_full_logged_total 2820
telemt_desync_suppressed_total 5655
telemt_desync_frames_bucket_total{bucket="1_2"} 1551
telemt_desync_frames_bucket_total{bucket="3_10"} 3307
telemt_desync_frames_bucket_total{bucket="gt_10"} 3617
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6039
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5840
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 1851860
telemt_user_connections_current{user="hello"} 4253
telemt_user_octets_from_client{user="hello"} 29748697872 (27.71 GB)
telemt_user_octets_to_client{user="hello"} 681198078684 (634.42 GB)
telemt_user_unique_ips_current{user="hello"} 1436
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 42937.0 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1948738
telemt_connections_bad_total 103263
telemt_connections_current 3118
telemt_connections_me_current 3118
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 49937
telemt_upstream_connect_attempt_total 15852
telemt_upstream_connect_success_total 15736
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 15852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7826
telemt_me_reconnect_success_total 5411
telemt_me_reader_eof_total 5752
telemt_me_idle_close_by_peer_total 5751
telemt_me_route_drop_no_conn_total 978820
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1460224
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5327
telemt_desync_full_logged_total 1810
telemt_desync_suppressed_total 3517
telemt_desync_frames_bucket_total{bucket="1_2"} 1107
telemt_desync_frames_bucket_total{bucket="3_10"} 2077
telemt_desync_frames_bucket_total{bucket="gt_10"} 2143
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5685
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5387
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 1466904
telemt_user_connections_current{user="hello"} 3118
telemt_user_octets_from_client{user="hello"} 17248480356 (16.06 GB)
telemt_user_octets_to_client{user="hello"} 426284397694 (397.01 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1016
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 42880.2 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2271425
telemt_connections_bad_total 547308
telemt_connections_current 3358
telemt_connections_me_current 3358
telemt_handshake_timeouts_total 48194
telemt_upstream_connect_attempt_total 7426
telemt_upstream_connect_success_total 7374
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 7426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5263
telemt_me_reconnect_success_total 5219
telemt_me_reader_eof_total 5529
telemt_me_idle_close_by_peer_total 5529
telemt_me_route_drop_no_conn_total 652756
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452847
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6700
telemt_desync_full_logged_total 2085
telemt_desync_suppressed_total 4615
telemt_desync_frames_bucket_total{bucket="1_2"} 1334
telemt_desync_frames_bucket_total{bucket="3_10"} 2949
telemt_desync_frames_bucket_total{bucket="gt_10"} 2417
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5296
telemt_me_writer_restored_same_endpoint_total 5195
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1452027
telemt_user_connections_current{user="hello"} 3358
telemt_user_octets_from_client{user="hello"} 27174902152 (25.31 GB)
telemt_user_octets_to_client{user="hello"} 639818233848 (595.88 GB)
telemt_user_unique_ips_current{user="hello"} 1177
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 42892.2 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403578
telemt_connections_bad_total 17853
telemt_connections_current 993
telemt_connections_me_current 993
telemt_handshake_timeouts_total 3242
telemt_upstream_connect_attempt_total 10876
telemt_upstream_connect_success_total 10604
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 10876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 13831
telemt_me_reconnect_success_total 8445
telemt_me_reader_eof_total 8964
telemt_me_idle_close_by_peer_total 8964
telemt_me_route_drop_no_conn_total 205548
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362207
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 588
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 382
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8681
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8415
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 362170
telemt_user_connections_current{user="hello"} 993
telemt_user_octets_from_client{user="hello"} 5345991800 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 143816725312 (133.94 GB)
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 42882.6 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532775
telemt_connections_bad_total 131556
telemt_connections_current 3051
telemt_connections_me_current 3051
telemt_handshake_timeouts_total 65933
telemt_upstream_connect_attempt_total 8709
telemt_upstream_connect_success_total 8708
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 7891
telemt_me_reconnect_success_total 6539
telemt_me_reader_eof_total 6925
telemt_me_idle_close_by_peer_total 6924
telemt_me_route_drop_no_conn_total 598631
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1278376
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7210
telemt_desync_full_logged_total 2367
telemt_desync_suppressed_total 4843
telemt_desync_frames_bucket_total{bucket="1_2"} 1369
telemt_desync_frames_bucket_total{bucket="3_10"} 2706
telemt_desync_frames_bucket_total{bucket="gt_10"} 3135
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6659
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6524
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 1277247
telemt_user_connections_current{user="hello"} 3051
telemt_user_octets_from_client{user="hello"} 17548264096 (16.34 GB)
telemt_user_octets_to_client{user="hello"} 621498120884 (578.82 GB)
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 426
```