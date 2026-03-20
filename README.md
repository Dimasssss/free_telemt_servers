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

# Server Metrics 2026-03-20 06:29:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 47534.0 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949330
telemt_connections_bad_total 59167
telemt_connections_current 1498
telemt_connections_me_current 1498
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25112
telemt_upstream_connect_attempt_total 9206
telemt_upstream_connect_success_total 9101
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 9206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5680
telemt_me_reconnect_success_total 5636
telemt_me_reader_eof_total 5971
telemt_me_idle_close_by_peer_total 5970
telemt_me_route_drop_no_conn_total 272404
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771673
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4067
telemt_desync_full_logged_total 1467
telemt_desync_suppressed_total 2600
telemt_desync_frames_bucket_total{bucket="1_2"} 797
telemt_desync_frames_bucket_total{bucket="3_10"} 1582
telemt_desync_frames_bucket_total{bucket="gt_10"} 1688
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 5697
telemt_me_writer_restored_same_endpoint_total 5623
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 771056
telemt_user_connections_current{user="hello"} 1498
telemt_user_octets_from_client{user="hello"} 33934261920 (31.60 GB)
telemt_user_octets_to_client{user="hello"} 266630461301 (248.32 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 63990.2 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4162567
telemt_connections_bad_total 387246
telemt_connections_current 4924
telemt_connections_me_current 4924
telemt_handshake_timeouts_total 97436
telemt_upstream_connect_attempt_total 12047
telemt_upstream_connect_success_total 11823
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11664
telemt_me_reconnect_success_total 7409
telemt_me_reader_eof_total 7917
telemt_me_idle_close_by_peer_total 7916
telemt_me_route_drop_no_conn_total 1867416
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3398490
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13649
telemt_desync_full_logged_total 4537
telemt_desync_suppressed_total 9112
telemt_desync_frames_bucket_total{bucket="1_2"} 2669
telemt_desync_frames_bucket_total{bucket="3_10"} 5312
telemt_desync_frames_bucket_total{bucket="gt_10"} 5668
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 7638
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7354
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 3398132
telemt_user_connections_current{user="hello"} 4924
telemt_user_octets_from_client{user="hello"} 50248152706 (46.80 GB)
telemt_user_octets_to_client{user="hello"} 1281388058926 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1648
telemt_user_unique_ips_recent_window{user="hello"} 626
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 63955.6 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3774050
telemt_connections_bad_total 264375
telemt_connections_current 4540
telemt_connections_me_current 4540
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 55300
telemt_upstream_connect_attempt_total 67659
telemt_upstream_connect_success_total 62932
telemt_upstream_connect_fail_total 4727
telemt_upstream_connect_attempts_per_request{bucket="1"} 67659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4727
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10338
telemt_me_reconnect_success_total 7358
telemt_me_reader_eof_total 7681
telemt_me_idle_close_by_peer_total 7680
telemt_me_route_drop_no_conn_total 3384282
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3105034
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11068
telemt_desync_full_logged_total 3391
telemt_desync_suppressed_total 7677
telemt_desync_frames_bucket_total{bucket="1_2"} 2589
telemt_desync_frames_bucket_total{bucket="3_10"} 4200
telemt_desync_frames_bucket_total{bucket="gt_10"} 4279
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 675
telemt_me_writer_removed_unexpected_total 8080
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7354
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 722
telemt_user_connections_total{user="hello"} 3155840
telemt_user_connections_current{user="hello"} 4540
telemt_user_octets_from_client{user="hello"} 43558617904 (40.57 GB)
telemt_user_octets_to_client{user="hello"} 820408109467 (764.06 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1315
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 1538.9 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185680
telemt_connections_bad_total 24219
telemt_connections_current 4124
telemt_connections_me_current 4124
telemt_handshake_timeouts_total 3436
telemt_upstream_connect_attempt_total 292
telemt_upstream_connect_success_total 291
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 177
telemt_me_reconnect_success_total 175
telemt_me_reader_eof_total 142
telemt_me_idle_close_by_peer_total 142
telemt_me_route_drop_no_conn_total 115180
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144546
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 164
telemt_me_writer_restored_same_endpoint_total 145
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 144405
telemt_user_connections_current{user="hello"} 4124
telemt_user_octets_from_client{user="hello"} 2207669584 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 40410921336 (37.64 GB)
telemt_user_unique_ips_current{user="hello"} 1382
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1473.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22500
telemt_connections_bad_total 3365
telemt_connections_current 504
telemt_connections_me_current 504
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 210
telemt_upstream_connect_success_total 209
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 98
telemt_me_reconnect_success_total 98
telemt_me_reader_eof_total 76
telemt_me_idle_close_by_peer_total 76
telemt_me_route_drop_no_conn_total 12883
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23445
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_restored_same_endpoint_total 90
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_user_connections_total{user="hello"} 17677
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 148044312 (141.19 MB)
telemt_user_octets_to_client{user="hello"} 6183637580 (5.76 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 63920.1 (17h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2716453
telemt_connections_bad_total 174843
telemt_connections_current 3857
telemt_connections_me_current 3857
telemt_handshake_timeouts_total 48027
telemt_upstream_connect_attempt_total 11324
telemt_upstream_connect_success_total 11255
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8150
telemt_me_reconnect_success_total 8099
telemt_me_reader_eof_total 8559
telemt_me_idle_close_by_peer_total 8559
telemt_me_route_drop_no_conn_total 932125
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2273018
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11353
telemt_desync_full_logged_total 3726
telemt_desync_suppressed_total 7627
telemt_desync_frames_bucket_total{bucket="1_2"} 2245
telemt_desync_frames_bucket_total{bucket="3_10"} 4006
telemt_desync_frames_bucket_total{bucket="gt_10"} 5102
telemt_pool_swap_total 65
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8210
telemt_me_writer_restored_same_endpoint_total 8082
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 2271875
telemt_user_connections_current{user="hello"} 3857
telemt_user_octets_from_client{user="hello"} 49723963420 (46.31 GB)
telemt_user_octets_to_client{user="hello"} 1194099967224 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 1270
telemt_user_unique_ips_recent_window{user="hello"} 490
```