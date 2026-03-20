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

# Server Metrics 2026-03-20 04:58:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 42026.8 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788262
telemt_connections_bad_total 52794
telemt_connections_current 1177
telemt_connections_me_current 1177
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17931
telemt_upstream_connect_attempt_total 8311
telemt_upstream_connect_success_total 8215
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 8311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5056
telemt_me_reconnect_success_total 5013
telemt_me_reader_eof_total 5307
telemt_me_idle_close_by_peer_total 5306
telemt_me_route_drop_no_conn_total 220469
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631999
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3396
telemt_desync_full_logged_total 1214
telemt_desync_suppressed_total 2182
telemt_desync_frames_bucket_total{bucket="1_2"} 658
telemt_desync_frames_bucket_total{bucket="3_10"} 1324
telemt_desync_frames_bucket_total{bucket="gt_10"} 1414
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 5060
telemt_me_writer_restored_same_endpoint_total 5000
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 633462
telemt_user_connections_current{user="hello"} 1177
telemt_user_octets_from_client{user="hello"} 32285530988 (30.07 GB)
telemt_user_octets_to_client{user="hello"} 216574357401 (201.70 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 58482.3 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3598923
telemt_connections_bad_total 307203
telemt_connections_current 3334
telemt_connections_me_current 3334
telemt_handshake_timeouts_total 77260
telemt_upstream_connect_attempt_total 11096
telemt_upstream_connect_success_total 10893
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 11096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11029
telemt_me_reconnect_success_total 6779
telemt_me_reader_eof_total 7251
telemt_me_idle_close_by_peer_total 7251
telemt_me_route_drop_no_conn_total 1632454
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2959122
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12286
telemt_desync_full_logged_total 4109
telemt_desync_suppressed_total 8177
telemt_desync_frames_bucket_total{bucket="1_2"} 2330
telemt_desync_frames_bucket_total{bucket="3_10"} 4772
telemt_desync_frames_bucket_total{bucket="gt_10"} 5184
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 56
telemt_me_writer_removed_unexpected_total 6995
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6724
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 2958817
telemt_user_connections_current{user="hello"} 3334
telemt_user_octets_from_client{user="hello"} 45030483182 (41.94 GB)
telemt_user_octets_to_client{user="hello"} 1121189716698 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1229
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 58460.2 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3286238
telemt_connections_bad_total 490149
telemt_connections_current 2597
telemt_connections_me_current 2597
telemt_handshake_timeouts_total 51725
telemt_upstream_connect_attempt_total 9474
telemt_upstream_connect_success_total 9409
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7463
telemt_me_reconnect_success_total 6522
telemt_me_reader_eof_total 6869
telemt_me_idle_close_by_peer_total 6868
telemt_me_route_drop_no_conn_total 2021777
telemt_me_route_drop_channel_closed_total 181
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2306054
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8516
telemt_desync_full_logged_total 2629
telemt_desync_suppressed_total 5887
telemt_desync_frames_bucket_total{bucket="1_2"} 2113
telemt_desync_frames_bucket_total{bucket="3_10"} 3248
telemt_desync_frames_bucket_total{bucket="gt_10"} 3155
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6592
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6521
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 2301083
telemt_user_connections_current{user="hello"} 2597
telemt_user_octets_from_client{user="hello"} 34935866012 (32.54 GB)
telemt_user_octets_to_client{user="hello"} 924893774056 (861.37 GB)
telemt_user_unique_ips_current{user="hello"} 946
telemt_user_unique_ips_recent_window{user="hello"} 323
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 58448.2 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2975045
telemt_connections_bad_total 224296
telemt_connections_current 2427
telemt_connections_me_current 2427
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 38600
telemt_upstream_connect_attempt_total 63451
telemt_upstream_connect_success_total 58892
telemt_upstream_connect_fail_total 4559
telemt_upstream_connect_attempts_per_request{bucket="1"} 63451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4559
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9798
telemt_me_reconnect_success_total 6865
telemt_me_reader_eof_total 7167
telemt_me_idle_close_by_peer_total 7166
telemt_me_route_drop_no_conn_total 2007392
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2415152
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9230
telemt_desync_full_logged_total 2950
telemt_desync_suppressed_total 6280
telemt_desync_frames_bucket_total{bucket="1_2"} 2214
telemt_desync_frames_bucket_total{bucket="3_10"} 3392
telemt_desync_frames_bucket_total{bucket="gt_10"} 3624
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7550
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6861
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 2462337
telemt_user_connections_current{user="hello"} 2427
telemt_user_octets_from_client{user="hello"} 38873414481 (36.20 GB)
telemt_user_octets_to_client{user="hello"} 740807727987 (689.93 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 112171.2 (31h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6733764
telemt_connections_bad_total 1183793
telemt_connections_current 2899
telemt_connections_me_current 2899
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 119958
telemt_upstream_connect_attempt_total 129485
telemt_upstream_connect_success_total 96185
telemt_upstream_connect_fail_total 33300
telemt_upstream_connect_attempts_per_request{bucket="1"} 129485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33300
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79970
telemt_me_reconnect_success_total 14291
telemt_me_reader_eof_total 15374
telemt_me_idle_close_by_peer_total 15360
telemt_me_route_drop_no_conn_total 2898973
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4746367
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
telemt_desync_total 20564
telemt_desync_full_logged_total 6542
telemt_desync_suppressed_total 14022
telemt_desync_frames_bucket_total{bucket="1_2"} 3643
telemt_desync_frames_bucket_total{bucket="3_10"} 8506
telemt_desync_frames_bucket_total{bucket="gt_10"} 8415
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 14617
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14266
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 4821428
telemt_user_connections_current{user="hello"} 2899
telemt_user_octets_from_client{user="hello"} 76307203912 (71.07 GB)
telemt_user_octets_to_client{user="hello"} 1899284486688 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1013
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 58411.4 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1441103
telemt_connections_bad_total 102865
telemt_connections_current 703
telemt_connections_me_current 703
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14082
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473461
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1531
telemt_desync_full_logged_total 573
telemt_desync_suppressed_total 958
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 680
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1265520
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 8614823903 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 146619936298 (136.55 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 58412.6 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2351305
telemt_connections_bad_total 152596
telemt_connections_current 2472
telemt_connections_me_current 2472
telemt_handshake_timeouts_total 43632
telemt_upstream_connect_attempt_total 10469
telemt_upstream_connect_success_total 10403
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7557
telemt_me_reconnect_success_total 7508
telemt_me_reader_eof_total 7931
telemt_me_idle_close_by_peer_total 7931
telemt_me_route_drop_no_conn_total 832246
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1976438
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10047
telemt_desync_full_logged_total 3248
telemt_desync_suppressed_total 6799
telemt_desync_frames_bucket_total{bucket="1_2"} 1969
telemt_desync_frames_bucket_total{bucket="3_10"} 3520
telemt_desync_frames_bucket_total{bucket="gt_10"} 4558
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7614
telemt_me_writer_restored_same_endpoint_total 7491
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 1975133
telemt_user_connections_current{user="hello"} 2472
telemt_user_octets_from_client{user="hello"} 42060372308 (39.17 GB)
telemt_user_octets_to_client{user="hello"} 1040538502892 (969.08 GB)
telemt_user_unique_ips_current{user="hello"} 887
telemt_user_unique_ips_recent_window{user="hello"} 296
```