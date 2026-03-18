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

# Server Metrics 2026-03-18 15:28:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 161.1 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8089
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 144
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 3485
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6642
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 6642
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 47622232 (45.42 MB)
telemt_user_octets_to_client{user="hello"} 1007068060 (960.41 MB)
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 4989.1 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568835
telemt_connections_bad_total 31149
telemt_connections_current 3615
telemt_connections_me_current 3615
telemt_handshake_timeouts_total 10985
telemt_upstream_connect_attempt_total 872
telemt_upstream_connect_success_total 866
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 578
telemt_me_reconnect_success_total 570
telemt_me_reader_eof_total 478
telemt_me_idle_close_by_peer_total 477
telemt_me_route_drop_no_conn_total 592069
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500075
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1226
telemt_desync_full_logged_total 375
telemt_desync_suppressed_total 851
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 485
telemt_desync_frames_bucket_total{bucket="gt_10"} 466
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 495
telemt_me_writer_restored_same_endpoint_total 568
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 499307
telemt_user_connections_current{user="hello"} 3615
telemt_user_octets_from_client{user="hello"} 4666052604 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 129066651356 (120.20 GB)
telemt_user_unique_ips_current{user="hello"} 1120
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 4918.0 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362394
telemt_connections_bad_total 22424
telemt_connections_current 2942
telemt_connections_me_current 2942
telemt_handshake_timeouts_total 6779
telemt_upstream_connect_attempt_total 663
telemt_upstream_connect_success_total 659
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 374
telemt_me_reconnect_success_total 370
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 215754
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313869
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1002
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 712
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 383
telemt_me_writer_restored_same_endpoint_total 353
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 313842
telemt_user_connections_current{user="hello"} 2942
telemt_user_octets_from_client{user="hello"} 6040793076 (5.63 GB)
telemt_user_octets_to_client{user="hello"} 116528072332 (108.53 GB)
telemt_user_unique_ips_current{user="hello"} 952
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 5631.8 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564092
telemt_connections_bad_total 5686
telemt_connections_current 2314
telemt_connections_me_current 2314
telemt_handshake_timeouts_total 7883
telemt_upstream_connect_attempt_total 927
telemt_upstream_connect_success_total 919
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 583
telemt_me_reconnect_success_total 575
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 1024945
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514440
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1678
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 557
telemt_me_writer_restored_same_endpoint_total 564
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 514413
telemt_user_connections_current{user="hello"} 2314
telemt_user_octets_from_client{user="hello"} 3468299152 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 82696202532 (77.02 GB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 146.4 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14281
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 115
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 47
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 8
telemt_me_idle_close_by_peer_total 8
telemt_me_route_drop_no_conn_total 3760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12114
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 30
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 12014
telemt_user_connections_current{user="hello"} 2880
telemt_user_octets_from_client{user="hello"} 67767992 (64.63 MB)
telemt_user_octets_to_client{user="hello"} 2933940216 (2.73 GB)
telemt_user_unique_ips_current{user="hello"} 897
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 5080.5 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106289
telemt_connections_bad_total 5661
telemt_connections_current 854
telemt_connections_me_current 854
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 961
telemt_upstream_connect_attempt_total 4978
telemt_upstream_connect_success_total 4971
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330314
telemt_me_reconnect_success_total 857
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 60402
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91169
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 187
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 780
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 846
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 94923
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 1584391161 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 18308172117 (17.05 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 4151.2 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280018
telemt_connections_bad_total 11525
telemt_connections_current 2645
telemt_connections_me_current 2645
telemt_handshake_timeouts_total 2528
telemt_upstream_connect_attempt_total 746
telemt_upstream_connect_success_total 746
telemt_upstream_connect_attempts_per_request{bucket="1"} 746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 332
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14790
telemt_me_reconnect_success_total 500
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 403
telemt_me_route_drop_no_conn_total 197323
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240831
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 563
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 412
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 439
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 241275
telemt_user_connections_current{user="hello"} 2645
telemt_user_octets_from_client{user="hello"} 2857852996 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 96517906624 (89.89 GB)
telemt_user_unique_ips_current{user="hello"} 791
telemt_user_unique_ips_recent_window{user="hello"} 323
```