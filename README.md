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

# Server Metrics 2026-03-20 01:08:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 28263.4 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538173
telemt_connections_bad_total 34928
telemt_connections_current 765
telemt_connections_me_current 765
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7718
telemt_upstream_connect_attempt_total 6048
telemt_upstream_connect_success_total 5967
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 6048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3455
telemt_me_reconnect_success_total 3420
telemt_me_reader_eof_total 3603
telemt_me_idle_close_by_peer_total 3602
telemt_me_route_drop_no_conn_total 157658
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429238
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2072
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 423
telemt_desync_frames_bucket_total{bucket="3_10"} 706
telemt_desync_frames_bucket_total{bucket="gt_10"} 943
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3441
telemt_me_writer_restored_same_endpoint_total 3407
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 430668
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 29538283656 (27.51 GB)
telemt_user_octets_to_client{user="hello"} 155215082325 (144.56 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 44718.0 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2970637
telemt_connections_bad_total 125733
telemt_connections_current 1332
telemt_connections_me_current 1332
telemt_handshake_timeouts_total 64517
telemt_upstream_connect_attempt_total 8925
telemt_upstream_connect_success_total 8779
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 8925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9561
telemt_me_reconnect_success_total 5322
telemt_me_reader_eof_total 5697
telemt_me_idle_close_by_peer_total 5697
telemt_me_route_drop_no_conn_total 1494736
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2543880
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10993
telemt_desync_full_logged_total 3618
telemt_desync_suppressed_total 7375
telemt_desync_frames_bucket_total{bucket="1_2"} 2093
telemt_desync_frames_bucket_total{bucket="3_10"} 4306
telemt_desync_frames_bucket_total{bucket="gt_10"} 4594
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5513
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5267
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 2543662
telemt_user_connections_current{user="hello"} 1332
telemt_user_octets_from_client{user="hello"} 39087104718 (36.40 GB)
telemt_user_octets_to_client{user="hello"} 927912995970 (864.19 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 44684.0 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2528556
telemt_connections_bad_total 116247
telemt_connections_current 980
telemt_connections_me_current 980
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30964
telemt_upstream_connect_attempt_total 55124
telemt_upstream_connect_success_total 50863
telemt_upstream_connect_fail_total 4261
telemt_upstream_connect_attempts_per_request{bucket="1"} 55124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4261
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8215
telemt_me_reconnect_success_total 5388
telemt_me_reader_eof_total 5589
telemt_me_idle_close_by_peer_total 5588
telemt_me_route_drop_no_conn_total 1858784
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2117495
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8273
telemt_desync_full_logged_total 2612
telemt_desync_suppressed_total 5661
telemt_desync_frames_bucket_total{bucket="1_2"} 2029
telemt_desync_frames_bucket_total{bucket="3_10"} 3013
telemt_desync_frames_bucket_total{bucket="gt_10"} 3231
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 476
telemt_me_writer_removed_unexpected_total 6007
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5384
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 2159564
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 35346196497 (32.92 GB)
telemt_user_octets_to_client{user="hello"} 604865482817 (563.32 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 98407.5 (27h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6241139
telemt_connections_bad_total 1040546
telemt_connections_current 1235
telemt_connections_me_current 1235
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 112524
telemt_upstream_connect_attempt_total 127153
telemt_upstream_connect_success_total 93869
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 127152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78301
telemt_me_reconnect_success_total 12630
telemt_me_reader_eof_total 13610
telemt_me_idle_close_by_peer_total 13596
telemt_me_route_drop_no_conn_total 2788665
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4419476
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
telemt_desync_total 19440
telemt_desync_full_logged_total 6150
telemt_desync_suppressed_total 13290
telemt_desync_frames_bucket_total{bucket="1_2"} 3415
telemt_desync_frames_bucket_total{bucket="3_10"} 7994
telemt_desync_frames_bucket_total{bucket="gt_10"} 8031
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 12937
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12605
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 4494690
telemt_user_connections_current{user="hello"} 1235
telemt_user_octets_from_client{user="hello"} 70594198196 (65.75 GB)
telemt_user_octets_to_client{user="hello"} 1733096428908 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 44647.2 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701573
telemt_connections_bad_total 73899
telemt_connections_current 351
telemt_connections_me_current 351
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12974
telemt_upstream_connect_attempt_total 13268
telemt_upstream_connect_success_total 12938
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6363
telemt_me_reconnect_success_total 6257
telemt_me_reader_eof_total 6558
telemt_me_idle_close_by_peer_total 6555
telemt_me_route_drop_no_conn_total 466220
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576634
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
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6315
telemt_me_writer_restored_same_endpoint_total 6248
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 564780
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 7268462727 (6.77 GB)
telemt_user_octets_to_client{user="hello"} 141463951494 (131.75 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 44648.7 (12h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1999715
telemt_connections_bad_total 119950
telemt_connections_current 1102
telemt_connections_me_current 1102
telemt_handshake_timeouts_total 37011
telemt_upstream_connect_attempt_total 7930
telemt_upstream_connect_success_total 7871
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 7930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5673
telemt_me_reconnect_success_total 5632
telemt_me_reader_eof_total 5943
telemt_me_idle_close_by_peer_total 5943
telemt_me_route_drop_no_conn_total 737536
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1723204
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9119
telemt_desync_full_logged_total 2928
telemt_desync_suppressed_total 6191
telemt_desync_frames_bucket_total{bucket="1_2"} 1700
telemt_desync_frames_bucket_total{bucket="3_10"} 3204
telemt_desync_frames_bucket_total{bucket="gt_10"} 4215
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 38
telemt_me_writer_removed_unexpected_total 5718
telemt_me_writer_restored_same_endpoint_total 5615
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 1722320
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 29504167684 (27.48 GB)
telemt_user_octets_to_client{user="hello"} 871595277356 (811.74 GB)
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 80
```