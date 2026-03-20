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

# Server Metrics 2026-03-20 00:48:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 27035.4 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523226
telemt_connections_bad_total 33883
telemt_connections_current 810
telemt_connections_me_current 810
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7570
telemt_upstream_connect_attempt_total 5786
telemt_upstream_connect_success_total 5710
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 5786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3272
telemt_me_reconnect_success_total 3242
telemt_me_reader_eof_total 3408
telemt_me_idle_close_by_peer_total 3407
telemt_me_route_drop_no_conn_total 153292
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416421
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2037
telemt_desync_full_logged_total 732
telemt_desync_suppressed_total 1305
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 931
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3259
telemt_me_writer_restored_same_endpoint_total 3229
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 417852
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 29432832196 (27.41 GB)
telemt_user_octets_to_client{user="hello"} 150926728593 (140.56 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 43490.9 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2951054
telemt_connections_bad_total 125408
telemt_connections_current 1282
telemt_connections_me_current 1282
telemt_handshake_timeouts_total 63875
telemt_upstream_connect_attempt_total 8743
telemt_upstream_connect_success_total 8599
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 8743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9424
telemt_me_reconnect_success_total 5185
telemt_me_reader_eof_total 5552
telemt_me_idle_close_by_peer_total 5552
telemt_me_route_drop_no_conn_total 1489710
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2525638
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10915
telemt_desync_full_logged_total 3592
telemt_desync_suppressed_total 7323
telemt_desync_frames_bucket_total{bucket="1_2"} 2070
telemt_desync_frames_bucket_total{bucket="3_10"} 4278
telemt_desync_frames_bucket_total{bucket="gt_10"} 4567
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5371
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5130
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2525424
telemt_user_connections_current{user="hello"} 1282
telemt_user_octets_from_client{user="hello"} 38930680910 (36.26 GB)
telemt_user_octets_to_client{user="hello"} 919947011750 (856.77 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 43469.1 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2886094
telemt_connections_bad_total 470142
telemt_connections_current 1060
telemt_connections_me_current 1060
telemt_handshake_timeouts_total 41059
telemt_upstream_connect_attempt_total 6956
telemt_upstream_connect_success_total 6904
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 6956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5650
telemt_me_reconnect_success_total 4718
telemt_me_reader_eof_total 4943
telemt_me_idle_close_by_peer_total 4942
telemt_me_route_drop_no_conn_total 1906237
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1998198
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7599
telemt_desync_full_logged_total 2302
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1870
telemt_desync_frames_bucket_total{bucket="3_10"} 2899
telemt_desync_frames_bucket_total{bucket="gt_10"} 2830
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 4764
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4717
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1993876
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 29630357076 (27.60 GB)
telemt_user_octets_to_client{user="hello"} 760156781356 (707.95 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 43456.9 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2501579
telemt_connections_bad_total 108847
telemt_connections_current 993
telemt_connections_me_current 993
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30486
telemt_upstream_connect_attempt_total 53931
telemt_upstream_connect_success_total 49749
telemt_upstream_connect_fail_total 4182
telemt_upstream_connect_attempts_per_request{bucket="1"} 53931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7168
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4182
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8022
telemt_me_reconnect_success_total 5241
telemt_me_reader_eof_total 5447
telemt_me_idle_close_by_peer_total 5446
telemt_me_route_drop_no_conn_total 1855453
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2102483
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8242
telemt_desync_full_logged_total 2600
telemt_desync_suppressed_total 5642
telemt_desync_frames_bucket_total{bucket="1_2"} 2025
telemt_desync_frames_bucket_total{bucket="3_10"} 2993
telemt_desync_frames_bucket_total{bucket="gt_10"} 3224
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5827
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5237
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 2143633
telemt_user_connections_current{user="hello"} 993
telemt_user_octets_from_client{user="hello"} 35203877159 (32.79 GB)
telemt_user_octets_to_client{user="hello"} 601074996407 (559.79 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 97180.3 (26h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6223372
telemt_connections_bad_total 1039856
telemt_connections_current 1294
telemt_connections_me_current 1294
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 112125
telemt_upstream_connect_attempt_total 126879
telemt_upstream_connect_success_total 93596
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 126879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78113
telemt_me_reconnect_success_total 12444
telemt_me_reader_eof_total 13407
telemt_me_idle_close_by_peer_total 13393
telemt_me_route_drop_no_conn_total 2783316
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4403343
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
telemt_desync_total 19383
telemt_desync_full_logged_total 6125
telemt_desync_suppressed_total 13258
telemt_desync_frames_bucket_total{bucket="1_2"} 3395
telemt_desync_frames_bucket_total{bucket="3_10"} 7963
telemt_desync_frames_bucket_total{bucket="gt_10"} 8025
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 12748
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12419
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4478558
telemt_user_connections_current{user="hello"} 1294
telemt_user_octets_from_client{user="hello"} 69870423812 (65.07 GB)
telemt_user_octets_to_client{user="hello"} 1728274091592 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 43420.2 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694392
telemt_connections_bad_total 71974
telemt_connections_current 325
telemt_connections_me_current 325
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12957
telemt_upstream_connect_attempt_total 13024
telemt_upstream_connect_success_total 12694
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6608
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6162
telemt_me_reconnect_success_total 6057
telemt_me_reader_eof_total 6347
telemt_me_idle_close_by_peer_total 6344
telemt_me_route_drop_no_conn_total 463983
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571557
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
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6112
telemt_me_writer_restored_same_endpoint_total 6048
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 559701
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 7190862363 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 137728908198 (128.27 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 43421.4 (12h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1986877
telemt_connections_bad_total 118862
telemt_connections_current 1079
telemt_connections_me_current 1079
telemt_handshake_timeouts_total 36756
telemt_upstream_connect_attempt_total 7675
telemt_upstream_connect_success_total 7619
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5464
telemt_me_reconnect_success_total 5424
telemt_me_reader_eof_total 5726
telemt_me_idle_close_by_peer_total 5726
telemt_me_route_drop_no_conn_total 733972
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1712144
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9043
telemt_desync_full_logged_total 2902
telemt_desync_suppressed_total 6141
telemt_desync_frames_bucket_total{bucket="1_2"} 1677
telemt_desync_frames_bucket_total{bucket="3_10"} 3188
telemt_desync_frames_bucket_total{bucket="gt_10"} 4178
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5509
telemt_me_writer_restored_same_endpoint_total 5407
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1711260
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 29408706716 (27.39 GB)
telemt_user_octets_to_client{user="hello"} 867482515828 (807.91 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 69
```