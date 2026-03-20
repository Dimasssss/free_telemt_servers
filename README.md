# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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

# Server Metrics 2026-03-20 06:45:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 48453.1 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979839
telemt_connections_bad_total 60230
telemt_connections_current 1746
telemt_connections_me_current 1746
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25873
telemt_upstream_connect_attempt_total 9355
telemt_upstream_connect_success_total 9249
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 9355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5784
telemt_me_reconnect_success_total 5740
telemt_me_reader_eof_total 6081
telemt_me_idle_close_by_peer_total 6080
telemt_me_route_drop_no_conn_total 281020
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 798912
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4142
telemt_desync_full_logged_total 1504
telemt_desync_suppressed_total 2638
telemt_desync_frames_bucket_total{bucket="1_2"} 813
telemt_desync_frames_bucket_total{bucket="3_10"} 1608
telemt_desync_frames_bucket_total{bucket="gt_10"} 1721
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 5803
telemt_me_writer_restored_same_endpoint_total 5727
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 798308
telemt_user_connections_current{user="hello"} 1746
telemt_user_octets_from_client{user="hello"} 34278843080 (31.92 GB)
telemt_user_octets_to_client{user="hello"} 275098441941 (256.21 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 64909.6 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4348130
telemt_connections_bad_total 411673
telemt_connections_current 5704
telemt_connections_me_current 5704
telemt_handshake_timeouts_total 98325
telemt_upstream_connect_attempt_total 12174
telemt_upstream_connect_success_total 11949
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 12174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11737
telemt_me_reconnect_success_total 7481
telemt_me_reader_eof_total 8002
telemt_me_idle_close_by_peer_total 8001
telemt_me_route_drop_no_conn_total 2068755
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3550892
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13963
telemt_desync_full_logged_total 4641
telemt_desync_suppressed_total 9322
telemt_desync_frames_bucket_total{bucket="1_2"} 2761
telemt_desync_frames_bucket_total{bucket="3_10"} 5433
telemt_desync_frames_bucket_total{bucket="gt_10"} 5769
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 7712
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7426
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 3550525
telemt_user_connections_current{user="hello"} 5704
telemt_user_octets_from_client{user="hello"} 51110823522 (47.60 GB)
telemt_user_octets_to_client{user="hello"} 1303400468906 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1727
telemt_user_unique_ips_recent_window{user="hello"} 804
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 64874.3 (18h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4026706
telemt_connections_bad_total 273337
telemt_connections_current 4736
telemt_connections_me_current 4736
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 58044
telemt_upstream_connect_attempt_total 67780
telemt_upstream_connect_success_total 63047
telemt_upstream_connect_fail_total 4732
telemt_upstream_connect_attempts_per_request{bucket="1"} 67779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4732
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10401
telemt_me_reconnect_success_total 7418
telemt_me_reader_eof_total 7747
telemt_me_idle_close_by_peer_total 7746
telemt_me_route_drop_no_conn_total 3899779
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3334539
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11566
telemt_desync_full_logged_total 3490
telemt_desync_suppressed_total 8076
telemt_desync_frames_bucket_total{bucket="1_2"} 2695
telemt_desync_frames_bucket_total{bucket="3_10"} 4462
telemt_desync_frames_bucket_total{bucket="gt_10"} 4409
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 676
telemt_me_writer_removed_unexpected_total 8143
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7414
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 3385536
telemt_user_connections_current{user="hello"} 4736
telemt_user_octets_from_client{user="hello"} 44299438492 (41.26 GB)
telemt_user_octets_to_client{user="hello"} 831078257507 (774.00 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1360
telemt_user_unique_ips_recent_window{user="hello"} 731
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 2457.4 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300091
telemt_connections_bad_total 33966
telemt_connections_current 4646
telemt_connections_me_current 4646
telemt_handshake_timeouts_total 6356
telemt_upstream_connect_attempt_total 414
telemt_upstream_connect_success_total 413
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 255
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 225
telemt_me_idle_close_by_peer_total 225
telemt_me_route_drop_no_conn_total 220977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238752
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 713
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 479
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 242
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 238656
telemt_user_connections_current{user="hello"} 4646
telemt_user_octets_from_client{user="hello"} 4504178492 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 63854937896 (59.47 GB)
telemt_user_unique_ips_current{user="hello"} 1462
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2392.6 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37598
telemt_connections_bad_total 7186
telemt_connections_current 630
telemt_connections_me_current 630
telemt_handshake_timeouts_total 435
telemt_upstream_connect_attempt_total 441
telemt_upstream_connect_success_total 436
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 280
telemt_me_reconnect_success_total 278
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 21533
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 153
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 279
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 28520
telemt_user_connections_current{user="hello"} 630
telemt_user_octets_from_client{user="hello"} 247777976 (236.30 MB)
telemt_user_octets_to_client{user="hello"} 10945439420 (10.19 GB)
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 64839.0 (18h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2792140
telemt_connections_bad_total 181789
telemt_connections_current 4127
telemt_connections_me_current 4127
telemt_handshake_timeouts_total 49575
telemt_upstream_connect_attempt_total 11459
telemt_upstream_connect_success_total 11387
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 11459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8229
telemt_me_reconnect_success_total 8175
telemt_me_reader_eof_total 8645
telemt_me_idle_close_by_peer_total 8645
telemt_me_route_drop_no_conn_total 953160
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2336691
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11691
telemt_desync_full_logged_total 3830
telemt_desync_suppressed_total 7861
telemt_desync_frames_bucket_total{bucket="1_2"} 2335
telemt_desync_frames_bucket_total{bucket="3_10"} 4111
telemt_desync_frames_bucket_total{bucket="gt_10"} 5245
telemt_pool_swap_total 66
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8289
telemt_me_writer_restored_same_endpoint_total 8158
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 2335548
telemt_user_connections_current{user="hello"} 4127
telemt_user_octets_from_client{user="hello"} 51226053420 (47.71 GB)
telemt_user_octets_to_client{user="hello"} 1225818208672 (1.11 TB)
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 480
```