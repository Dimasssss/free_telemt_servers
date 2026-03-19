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

# Server Metrics 2026-03-19 10:03:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 44105.8 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959747
telemt_connections_bad_total 84844
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_handshake_timeouts_total 35396
telemt_upstream_connect_attempt_total 8323
telemt_upstream_connect_success_total 8178
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 8323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7144
telemt_me_reconnect_success_total 5986
telemt_me_reader_eof_total 6348
telemt_me_idle_close_by_peer_total 6347
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 324708
telemt_me_route_drop_channel_closed_total 131
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 738052
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4447
telemt_desync_full_logged_total 1347
telemt_desync_suppressed_total 3100
telemt_desync_frames_bucket_total{bucket="1_2"} 1489
telemt_desync_frames_bucket_total{bucket="3_10"} 1629
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6097
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5966
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 732430
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 11561460472 (10.77 GB)
telemt_user_octets_to_client{user="hello"} 233806117616 (217.75 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 44110.2 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2377015
telemt_connections_bad_total 148764
telemt_connections_current 4468
telemt_connections_me_current 4468
telemt_handshake_timeouts_total 52866
telemt_upstream_connect_attempt_total 8339
telemt_upstream_connect_success_total 8185
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 8339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8321
telemt_me_reconnect_success_total 5972
telemt_me_reader_eof_total 6358
telemt_me_idle_close_by_peer_total 6358
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1049545
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963385
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9009
telemt_desync_full_logged_total 2984
telemt_desync_suppressed_total 6025
telemt_desync_frames_bucket_total{bucket="1_2"} 1653
telemt_desync_frames_bucket_total{bucket="3_10"} 3510
telemt_desync_frames_bucket_total{bucket="gt_10"} 3846
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6154
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5950
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1963103
telemt_user_connections_current{user="hello"} 4468
telemt_user_octets_from_client{user="hello"} 30999806484 (28.87 GB)
telemt_user_octets_to_client{user="hello"} 712222645192 (663.31 GB)
telemt_user_unique_ips_current{user="hello"} 1443
telemt_user_unique_ips_recent_window{user="hello"} 1110
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 44175.6 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2045036
telemt_connections_bad_total 114521
telemt_connections_current 3105
telemt_connections_me_current 3105
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 53180
telemt_upstream_connect_attempt_total 16125
telemt_upstream_connect_success_total 15998
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 16125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8035
telemt_me_reconnect_success_total 5607
telemt_me_reader_eof_total 5957
telemt_me_idle_close_by_peer_total 5956
telemt_me_route_drop_no_conn_total 1032529
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1538617
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5629
telemt_desync_full_logged_total 1912
telemt_desync_suppressed_total 3717
telemt_desync_frames_bucket_total{bucket="1_2"} 1168
telemt_desync_frames_bucket_total{bucket="3_10"} 2202
telemt_desync_frames_bucket_total{bucket="gt_10"} 2259
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5890
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5583
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 1545263
telemt_user_connections_current{user="hello"} 3105
telemt_user_octets_from_client{user="hello"} 18016579196 (16.78 GB)
telemt_user_octets_to_client{user="hello"} 448358185890 (417.57 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 44104.0 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2378624
telemt_connections_bad_total 560733
telemt_connections_current 3704
telemt_connections_me_current 3704
telemt_handshake_timeouts_total 49735
telemt_upstream_connect_attempt_total 7703
telemt_upstream_connect_success_total 7649
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 7702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5492
telemt_me_reconnect_success_total 5446
telemt_me_reader_eof_total 5759
telemt_me_idle_close_by_peer_total 5759
telemt_me_route_drop_no_conn_total 699759
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1537142
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7118
telemt_desync_full_logged_total 2221
telemt_desync_suppressed_total 4897
telemt_desync_frames_bucket_total{bucket="1_2"} 1441
telemt_desync_frames_bucket_total{bucket="3_10"} 3093
telemt_desync_frames_bucket_total{bucket="gt_10"} 2584
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5527
telemt_me_writer_restored_same_endpoint_total 5422
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1536283
telemt_user_connections_current{user="hello"} 3705
telemt_user_octets_from_client{user="hello"} 28445717628 (26.49 GB)
telemt_user_octets_to_client{user="hello"} 671123924820 (625.03 GB)
telemt_user_unique_ips_current{user="hello"} 1235
telemt_user_unique_ips_recent_window{user="hello"} 740
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 44115.7 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426587
telemt_connections_bad_total 18166
telemt_connections_current 1048
telemt_connections_me_current 1048
telemt_handshake_timeouts_total 3377
telemt_upstream_connect_attempt_total 11110
telemt_upstream_connect_success_total 10830
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 11110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14014
telemt_me_reconnect_success_total 8626
telemt_me_reader_eof_total 9148
telemt_me_idle_close_by_peer_total 9148
telemt_me_route_drop_no_conn_total 215632
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383494
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 448
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8866
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8596
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 383462
telemt_user_connections_current{user="hello"} 1048
telemt_user_octets_from_client{user="hello"} 6135772064 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 149974617868 (139.67 GB)
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 44106.5 (12h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1615356
telemt_connections_bad_total 134115
telemt_connections_current 3463
telemt_connections_me_current 3463
telemt_handshake_timeouts_total 67445
telemt_upstream_connect_attempt_total 8873
telemt_upstream_connect_success_total 8872
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8012
telemt_me_reconnect_success_total 6660
telemt_me_reader_eof_total 7059
telemt_me_idle_close_by_peer_total 7058
telemt_me_route_drop_no_conn_total 643263
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1350128
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7582
telemt_desync_full_logged_total 2485
telemt_desync_suppressed_total 5097
telemt_desync_frames_bucket_total{bucket="1_2"} 1437
telemt_desync_frames_bucket_total{bucket="3_10"} 2849
telemt_desync_frames_bucket_total{bucket="gt_10"} 3296
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6783
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6645
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 1348964
telemt_user_connections_current{user="hello"} 3463
telemt_user_octets_from_client{user="hello"} 18411925884 (17.15 GB)
telemt_user_octets_to_client{user="hello"} 653133996216 (608.28 GB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 718
```