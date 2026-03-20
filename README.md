# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 01:34:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 29794.8 (8h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561552
telemt_connections_bad_total 36340
telemt_connections_current 808
telemt_connections_me_current 808
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8719
telemt_upstream_connect_attempt_total 6322
telemt_upstream_connect_success_total 6238
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 6322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3645
telemt_me_reconnect_success_total 3610
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3802
telemt_me_route_drop_no_conn_total 162621
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448431
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2113
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1355
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 724
telemt_desync_frames_bucket_total{bucket="gt_10"} 961
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3633
telemt_me_writer_restored_same_endpoint_total 3597
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 449860
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 29734143540 (27.69 GB)
telemt_user_octets_to_client{user="hello"} 160472687173 (149.45 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 46249.4 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2995768
telemt_connections_bad_total 125865
telemt_connections_current 1440
telemt_connections_me_current 1440
telemt_handshake_timeouts_total 65980
telemt_upstream_connect_attempt_total 9228
telemt_upstream_connect_success_total 9075
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 9228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9772
telemt_me_reconnect_success_total 5530
telemt_me_reader_eof_total 5920
telemt_me_idle_close_by_peer_total 5920
telemt_me_route_drop_no_conn_total 1502251
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2566972
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11108
telemt_desync_full_logged_total 3655
telemt_desync_suppressed_total 7453
telemt_desync_frames_bucket_total{bucket="1_2"} 2127
telemt_desync_frames_bucket_total{bucket="3_10"} 4346
telemt_desync_frames_bucket_total{bucket="gt_10"} 4635
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5724
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5475
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 2566753
telemt_user_connections_current{user="hello"} 1440
telemt_user_octets_from_client{user="hello"} 39284458034 (36.59 GB)
telemt_user_octets_to_client{user="hello"} 937679506286 (873.28 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 46227.5 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2945417
telemt_connections_bad_total 474593
telemt_connections_current 1058
telemt_connections_me_current 1058
telemt_handshake_timeouts_total 42999
telemt_upstream_connect_attempt_total 7464
telemt_upstream_connect_success_total 7408
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6022
telemt_me_reconnect_success_total 5089
telemt_me_reader_eof_total 5339
telemt_me_idle_close_by_peer_total 5338
telemt_me_route_drop_no_conn_total 1919217
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031344
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7632
telemt_desync_full_logged_total 2316
telemt_desync_suppressed_total 5316
telemt_desync_frames_bucket_total{bucket="1_2"} 1880
telemt_desync_frames_bucket_total{bucket="3_10"} 2910
telemt_desync_frames_bucket_total{bucket="gt_10"} 2842
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 5139
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5088
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2026971
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 29935476892 (27.88 GB)
telemt_user_octets_to_client{user="hello"} 773878672004 (720.73 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 46215.4 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2558215
telemt_connections_bad_total 125934
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31113
telemt_upstream_connect_attempt_total 55415
telemt_upstream_connect_success_total 51138
telemt_upstream_connect_fail_total 4277
telemt_upstream_connect_attempts_per_request{bucket="1"} 55415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4277
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8413
telemt_me_reconnect_success_total 5574
telemt_me_reader_eof_total 5791
telemt_me_idle_close_by_peer_total 5790
telemt_me_route_drop_no_conn_total 1862971
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2134460
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8329
telemt_desync_full_logged_total 2629
telemt_desync_suppressed_total 5700
telemt_desync_frames_bucket_total{bucket="1_2"} 2059
telemt_desync_frames_bucket_total{bucket="3_10"} 3024
telemt_desync_frames_bucket_total{bucket="gt_10"} 3246
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6197
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5570
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 623
telemt_user_connections_total{user="hello"} 2176532
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 35500341897 (33.06 GB)
telemt_user_octets_to_client{user="hello"} 611946460469 (569.92 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 99938.5 (27h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6265798
telemt_connections_bad_total 1042655
telemt_connections_current 1256
telemt_connections_me_current 1256
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113344
telemt_upstream_connect_attempt_total 127373
telemt_upstream_connect_success_total 94090
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78469
telemt_me_reconnect_success_total 12799
telemt_me_reader_eof_total 13785
telemt_me_idle_close_by_peer_total 13771
telemt_me_route_drop_no_conn_total 2796119
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4440183
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19527
telemt_desync_full_logged_total 6185
telemt_desync_suppressed_total 13342
telemt_desync_frames_bucket_total{bucket="1_2"} 3432
telemt_desync_frames_bucket_total{bucket="3_10"} 8038
telemt_desync_frames_bucket_total{bucket="gt_10"} 8057
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 13107
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12774
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 4515397
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 72458936876 (67.48 GB)
telemt_user_octets_to_client{user="hello"} 1738802424928 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 46178.5 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709662
telemt_connections_bad_total 75934
telemt_connections_current 337
telemt_connections_me_current 337
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13011
telemt_upstream_connect_attempt_total 13609
telemt_upstream_connect_success_total 13279
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6618
telemt_me_reconnect_success_total 6511
telemt_me_reader_eof_total 6835
telemt_me_idle_close_by_peer_total 6832
telemt_me_route_drop_no_conn_total 469258
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 582503
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6572
telemt_me_writer_restored_same_endpoint_total 6502
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 570649
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 7326691759 (6.82 GB)
telemt_user_octets_to_client{user="hello"} 145050425074 (135.09 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 46180.0 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2015036
telemt_connections_bad_total 120015
telemt_connections_current 1153
telemt_connections_me_current 1153
telemt_handshake_timeouts_total 37450
telemt_upstream_connect_attempt_total 8246
telemt_upstream_connect_success_total 8186
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5902
telemt_me_reconnect_success_total 5860
telemt_me_reader_eof_total 6186
telemt_me_idle_close_by_peer_total 6186
telemt_me_route_drop_no_conn_total 742389
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1737126
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9208
telemt_desync_full_logged_total 2955
telemt_desync_suppressed_total 6253
telemt_desync_frames_bucket_total{bucket="1_2"} 1732
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 4247
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 5947
telemt_me_writer_restored_same_endpoint_total 5843
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 1736234
telemt_user_connections_current{user="hello"} 1153
telemt_user_octets_from_client{user="hello"} 29661246384 (27.62 GB)
telemt_user_octets_to_client{user="hello"} 880433445304 (819.97 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 94
```