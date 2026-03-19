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

# Server Metrics 2026-03-19 07:25:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 34600.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598556
telemt_connections_bad_total 61714
telemt_connections_current 1456
telemt_connections_me_current 1456
telemt_handshake_timeouts_total 23632
telemt_upstream_connect_attempt_total 6698
telemt_upstream_connect_success_total 6574
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 6698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 5984
telemt_me_reconnect_success_total 4834
telemt_me_reader_eof_total 5133
telemt_me_idle_close_by_peer_total 5132
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 169219
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 449820
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3029
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 2173
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1143
telemt_desync_frames_bucket_total{bucket="gt_10"} 823
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4924
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4817
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 446941
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 5983585164 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 150122451788 (139.81 GB)
telemt_user_unique_ips_current{user="hello"} 507
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 34604.4 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1396037
telemt_connections_bad_total 79290
telemt_connections_current 3800
telemt_connections_me_current 3800
telemt_handshake_timeouts_total 33239
telemt_upstream_connect_attempt_total 6517
telemt_upstream_connect_success_total 6392
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 6517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5794
telemt_me_reconnect_success_total 4640
telemt_me_reader_eof_total 4929
telemt_me_idle_close_by_peer_total 4929
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 588555
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1146942
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5074
telemt_desync_full_logged_total 1708
telemt_desync_suppressed_total 3366
telemt_desync_frames_bucket_total{bucket="1_2"} 921
telemt_desync_frames_bucket_total{bucket="3_10"} 1901
telemt_desync_frames_bucket_total{bucket="gt_10"} 2252
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4762
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4619
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 1146862
telemt_user_connections_current{user="hello"} 3800
telemt_user_octets_from_client{user="hello"} 21515723792 (20.04 GB)
telemt_user_octets_to_client{user="hello"} 463539894824 (431.71 GB)
telemt_user_unique_ips_current{user="hello"} 1323
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 34654.6 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1242421
telemt_connections_bad_total 89575
telemt_connections_current 2776
telemt_connections_me_current 2776
telemt_handshake_timeouts_total 30846
telemt_upstream_connect_attempt_total 6053
telemt_upstream_connect_success_total 6053
telemt_upstream_connect_attempts_per_request{bucket="1"} 6053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5353
telemt_me_reconnect_success_total 4292
telemt_me_reader_eof_total 4564
telemt_me_idle_close_by_peer_total 4563
telemt_me_route_drop_no_conn_total 449923
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 845374
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3191
telemt_desync_full_logged_total 1117
telemt_desync_suppressed_total 2074
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1259
telemt_desync_frames_bucket_total{bucket="gt_10"} 1344
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4386
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4268
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 844208
telemt_user_connections_current{user="hello"} 2776
telemt_user_octets_from_client{user="hello"} 12224532016 (11.38 GB)
telemt_user_octets_to_client{user="hello"} 298847080160 (278.32 GB)
telemt_user_unique_ips_current{user="hello"} 967
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 34598.0 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491095
telemt_connections_bad_total 416634
telemt_connections_current 3200
telemt_connections_me_current 3200
telemt_handshake_timeouts_total 32185
telemt_upstream_connect_attempt_total 6100
telemt_upstream_connect_success_total 6063
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4349
telemt_me_reconnect_success_total 4317
telemt_me_reader_eof_total 4576
telemt_me_idle_close_by_peer_total 4576
telemt_me_route_drop_no_conn_total 371366
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892169
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4405
telemt_desync_full_logged_total 1375
telemt_desync_suppressed_total 3030
telemt_desync_frames_bucket_total{bucket="1_2"} 983
telemt_desync_frames_bucket_total{bucket="3_10"} 1985
telemt_desync_frames_bucket_total{bucket="gt_10"} 1437
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4373
telemt_me_writer_restored_same_endpoint_total 4293
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 891871
telemt_user_connections_current{user="hello"} 3200
telemt_user_octets_from_client{user="hello"} 19365685644 (18.04 GB)
telemt_user_octets_to_client{user="hello"} 442658193072 (412.26 GB)
telemt_user_unique_ips_current{user="hello"} 1090
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 34609.9 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249806
telemt_connections_bad_total 13055
telemt_connections_current 869
telemt_connections_me_current 869
telemt_handshake_timeouts_total 2196
telemt_upstream_connect_attempt_total 9117
telemt_upstream_connect_success_total 8883
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 9117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12508
telemt_me_reconnect_success_total 7134
telemt_me_reader_eof_total 7580
telemt_me_idle_close_by_peer_total 7580
telemt_me_route_drop_no_conn_total 117980
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221652
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 354
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7344
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7104
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 221629
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 3398956616 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 110533824680 (102.94 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 34600.5 (9h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 938695
telemt_connections_bad_total 90595
telemt_connections_current 2867
telemt_connections_me_current 2867
telemt_handshake_timeouts_total 40343
telemt_upstream_connect_attempt_total 7085
telemt_upstream_connect_success_total 7085
telemt_upstream_connect_attempts_per_request{bucket="1"} 7085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6672
telemt_me_reconnect_success_total 5339
telemt_me_reader_eof_total 5669
telemt_me_idle_close_by_peer_total 5669
telemt_me_route_drop_no_conn_total 381357
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4513
telemt_desync_full_logged_total 1508
telemt_desync_suppressed_total 3005
telemt_desync_frames_bucket_total{bucket="1_2"} 894
telemt_desync_frames_bucket_total{bucket="3_10"} 1726
telemt_desync_frames_bucket_total{bucket="gt_10"} 1893
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5438
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5324
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 771084
telemt_user_connections_current{user="hello"} 2867
telemt_user_octets_from_client{user="hello"} 11338561664 (10.56 GB)
telemt_user_octets_to_client{user="hello"} 424762146232 (395.59 GB)
telemt_user_unique_ips_current{user="hello"} 948
telemt_user_unique_ips_recent_window{user="hello"} 392
```