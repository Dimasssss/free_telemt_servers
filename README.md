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

# Server Metrics 2026-03-18 14:57:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 22566.9 (6h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841526
telemt_connections_bad_total 60201
telemt_handshake_timeouts_total 23244
telemt_upstream_connect_attempt_total 67195
telemt_upstream_connect_success_total 66226
telemt_upstream_connect_fail_total 969
telemt_upstream_connect_attempts_per_request{bucket="1"} 67195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 969
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 518627
telemt_me_reconnect_success_total 3105
telemt_me_reader_eof_total 3399
telemt_me_idle_close_by_peer_total 3397
telemt_me_route_drop_no_conn_total 458140
telemt_me_route_drop_channel_closed_total 178
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644471
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2907
telemt_desync_full_logged_total 1002
telemt_desync_suppressed_total 1905
telemt_desync_frames_bucket_total{bucket="1_2"} 819
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 1110
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3404
telemt_me_refill_failed_total 16792
telemt_me_writer_restored_same_endpoint_total 2999
telemt_me_writer_restored_fallback_total 106
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 702550
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 10437663716 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 184828016777 (172.13 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 3135.5 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319187
telemt_connections_bad_total 18671
telemt_connections_current 3649
telemt_connections_me_current 3649
telemt_handshake_timeouts_total 7278
telemt_upstream_connect_attempt_total 517
telemt_upstream_connect_success_total 514
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 316
telemt_me_reconnect_success_total 311
telemt_me_reader_eof_total 217
telemt_me_idle_close_by_peer_total 216
telemt_me_route_drop_no_conn_total 167611
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 277567
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 230
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 276822
telemt_user_connections_current{user="hello"} 3649
telemt_user_octets_from_client{user="hello"} 3078292028 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 90041948492 (83.86 GB)
telemt_user_unique_ips_current{user="hello"} 1179
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 3777.9 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338668
telemt_connections_bad_total 1724
telemt_connections_current 2757
telemt_connections_me_current 2757
telemt_handshake_timeouts_total 6219
telemt_upstream_connect_attempt_total 651
telemt_upstream_connect_success_total 648
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 401
telemt_me_reconnect_success_total 394
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 362
telemt_me_route_drop_no_conn_total 432774
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301982
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 837
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 294
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 301923
telemt_user_connections_current{user="hello"} 2757
telemt_user_octets_from_client{user="hello"} 2504563724 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 54552725896 (50.81 GB)
telemt_user_unique_ips_current{user="hello"} 837
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 22437.8 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1833929
telemt_connections_bad_total 146191
telemt_handshake_timeouts_total 29025
telemt_upstream_connect_attempt_total 15454
telemt_upstream_connect_success_total 15426
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 15454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2987070
telemt_me_reconnect_success_total 2630
telemt_me_reader_eof_total 2748
telemt_me_idle_close_by_peer_total 2748
telemt_me_route_drop_no_conn_total 1889879
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525161
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4339
telemt_desync_full_logged_total 1521
telemt_desync_suppressed_total 2818
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1942
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2702
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 2515
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1526988
telemt_user_connections_current{user="hello"} 2994
telemt_user_octets_from_client{user="hello"} 23756515067 (22.12 GB)
telemt_user_octets_to_client{user="hello"} 511615132089 (476.48 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 3227.6 (0h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73922
telemt_connections_bad_total 4551
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 783
telemt_upstream_connect_attempt_total 4664
telemt_upstream_connect_success_total 4658
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 4664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 330088
telemt_me_reconnect_success_total 633
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 43053
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61554
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 550
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 622
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 65324
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 1134124821 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 10843413613 (10.10 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 2297.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168083
telemt_connections_bad_total 5824
telemt_connections_current 2595
telemt_connections_me_current 2595
telemt_handshake_timeouts_total 1324
telemt_upstream_connect_attempt_total 494
telemt_upstream_connect_success_total 494
telemt_upstream_connect_attempts_per_request{bucket="1"} 494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14624
telemt_me_reconnect_success_total 336
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 154247
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147907
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 374
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 249
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 243
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 275
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 148763
telemt_user_connections_current{user="hello"} 2595
telemt_user_octets_from_client{user="hello"} 1491614300 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 43944175548 (40.93 GB)
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 349
```