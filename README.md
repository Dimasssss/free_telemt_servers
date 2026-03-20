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

# Server Metrics 2026-03-20 04:27:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 40193.0 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 745131
telemt_connections_bad_total 51093
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17351
telemt_upstream_connect_attempt_total 8034
telemt_upstream_connect_success_total 7939
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 8034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4866
telemt_me_reconnect_success_total 4825
telemt_me_reader_eof_total 5107
telemt_me_idle_close_by_peer_total 5106
telemt_me_route_drop_no_conn_total 209384
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 593059
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3136
telemt_desync_full_logged_total 1121
telemt_desync_suppressed_total 2015
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1201
telemt_desync_frames_bucket_total{bucket="gt_10"} 1318
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 4870
telemt_me_writer_restored_same_endpoint_total 4812
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 594483
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 31881494724 (29.69 GB)
telemt_user_octets_to_client{user="hello"} 202271851713 (188.38 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 56648.6 (15h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3457665
telemt_connections_bad_total 273505
telemt_connections_current 2978
telemt_connections_me_current 2978
telemt_handshake_timeouts_total 74706
telemt_upstream_connect_attempt_total 10833
telemt_upstream_connect_success_total 10636
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 10833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10860
telemt_me_reconnect_success_total 6610
telemt_me_reader_eof_total 7072
telemt_me_idle_close_by_peer_total 7072
telemt_me_route_drop_no_conn_total 1598543
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2862322
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12014
telemt_desync_full_logged_total 4006
telemt_desync_suppressed_total 8008
telemt_desync_frames_bucket_total{bucket="1_2"} 2300
telemt_desync_frames_bucket_total{bucket="3_10"} 4674
telemt_desync_frames_bucket_total{bucket="gt_10"} 5040
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 6823
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6555
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 2861988
telemt_user_connections_current{user="hello"} 2978
telemt_user_octets_from_client{user="hello"} 43671112086 (40.67 GB)
telemt_user_octets_to_client{user="hello"} 1078821859190 (1004.73 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1092
telemt_user_unique_ips_recent_window{user="hello"} 398
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 56626.6 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3203716
telemt_connections_bad_total 486722
telemt_connections_current 2258
telemt_connections_me_current 2258
telemt_handshake_timeouts_total 50606
telemt_upstream_connect_attempt_total 9215
telemt_upstream_connect_success_total 9150
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7290
telemt_me_reconnect_success_total 6351
telemt_me_reader_eof_total 6682
telemt_me_idle_close_by_peer_total 6681
telemt_me_route_drop_no_conn_total 1999464
telemt_me_route_drop_channel_closed_total 178
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2235726
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8236
telemt_desync_full_logged_total 2534
telemt_desync_suppressed_total 5702
telemt_desync_frames_bucket_total{bucket="1_2"} 2036
telemt_desync_frames_bucket_total{bucket="3_10"} 3139
telemt_desync_frames_bucket_total{bucket="gt_10"} 3061
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6415
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6350
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 2230753
telemt_user_connections_current{user="hello"} 2258
telemt_user_octets_from_client{user="hello"} 34005992340 (31.67 GB)
telemt_user_octets_to_client{user="hello"} 888918339188 (827.87 GB)
telemt_user_unique_ips_current{user="hello"} 795
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 56614.4 (15h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2895737
telemt_connections_bad_total 220351
telemt_connections_current 2145
telemt_connections_me_current 2145
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 35327
telemt_upstream_connect_attempt_total 63192
telemt_upstream_connect_success_total 58637
telemt_upstream_connect_fail_total 4555
telemt_upstream_connect_attempts_per_request{bucket="1"} 63192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4555
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9627
telemt_me_reconnect_success_total 6699
telemt_me_reader_eof_total 6989
telemt_me_idle_close_by_peer_total 6988
telemt_me_route_drop_no_conn_total 1968799
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2345959
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8970
telemt_desync_full_logged_total 2865
telemt_desync_suppressed_total 6105
telemt_desync_frames_bucket_total{bucket="1_2"} 2176
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 3513
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7379
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6695
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 2393300
telemt_user_connections_current{user="hello"} 2145
telemt_user_octets_from_client{user="hello"} 37944169153 (35.34 GB)
telemt_user_octets_to_client{user="hello"} 712577183255 (663.64 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 110337.5 (30h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6639848
telemt_connections_bad_total 1169511
telemt_connections_current 2481
telemt_connections_me_current 2481
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 118768
telemt_upstream_connect_attempt_total 129209
telemt_upstream_connect_success_total 95913
telemt_upstream_connect_fail_total 33296
telemt_upstream_connect_attempts_per_request{bucket="1"} 129209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33296
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79784
telemt_me_reconnect_success_total 14106
telemt_me_reader_eof_total 15177
telemt_me_idle_close_by_peer_total 15163
telemt_me_route_drop_no_conn_total 2874061
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4670914
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
telemt_desync_total 20225
telemt_desync_full_logged_total 6441
telemt_desync_suppressed_total 13784
telemt_desync_frames_bucket_total{bucket="1_2"} 3566
telemt_desync_frames_bucket_total{bucket="3_10"} 8373
telemt_desync_frames_bucket_total{bucket="gt_10"} 8286
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 14429
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14081
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 4745983
telemt_user_connections_current{user="hello"} 2481
telemt_user_octets_from_client{user="hello"} 75188993008 (70.03 GB)
telemt_user_octets_to_client{user="hello"} 1858599412348 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 920
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 56577.5 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1333004
telemt_connections_bad_total 94996
telemt_connections_current 504
telemt_connections_me_current 504
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13787
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
telemt_me_route_drop_no_conn_total 473310
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
telemt_desync_total 1490
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 926
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 643
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
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
telemt_user_connections_total{user="hello"} 1167439
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 8301931107 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 146612866550 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 56579.0 (15h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2263194
telemt_connections_bad_total 148248
telemt_connections_current 2204
telemt_connections_me_current 2204
telemt_handshake_timeouts_total 42919
telemt_upstream_connect_attempt_total 10160
telemt_upstream_connect_success_total 10094
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7334
telemt_me_reconnect_success_total 7285
telemt_me_reader_eof_total 7697
telemt_me_idle_close_by_peer_total 7697
telemt_me_route_drop_no_conn_total 810718
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1913667
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9755
telemt_desync_full_logged_total 3152
telemt_desync_suppressed_total 6603
telemt_desync_frames_bucket_total{bucket="1_2"} 1918
telemt_desync_frames_bucket_total{bucket="3_10"} 3416
telemt_desync_frames_bucket_total{bucket="gt_10"} 4421
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7389
telemt_me_writer_restored_same_endpoint_total 7268
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 1912440
telemt_user_connections_current{user="hello"} 2204
telemt_user_octets_from_client{user="hello"} 41128049744 (38.30 GB)
telemt_user_octets_to_client{user="hello"} 997773906012 (929.25 GB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 256
```