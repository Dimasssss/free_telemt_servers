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

# Server Metrics 2026-03-20 04:07:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 38971.0 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719105
telemt_connections_bad_total 49911
telemt_connections_current 1130
telemt_connections_me_current 1130
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 16009
telemt_upstream_connect_attempt_total 7876
telemt_upstream_connect_success_total 7781
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 7876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4751
telemt_me_reconnect_success_total 4711
telemt_me_reader_eof_total 4987
telemt_me_idle_close_by_peer_total 4986
telemt_me_route_drop_no_conn_total 203001
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571097
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2884
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 1840
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 1091
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 43
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4754
telemt_me_writer_restored_same_endpoint_total 4698
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 572502
telemt_user_connections_current{user="hello"} 1130
telemt_user_octets_from_client{user="hello"} 31589632008 (29.42 GB)
telemt_user_octets_to_client{user="hello"} 195474431669 (182.05 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 55426.8 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3366525
telemt_connections_bad_total 243527
telemt_connections_current 2486
telemt_connections_me_current 2486
telemt_handshake_timeouts_total 72476
telemt_upstream_connect_attempt_total 10675
telemt_upstream_connect_success_total 10484
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 10675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10751
telemt_me_reconnect_success_total 6502
telemt_me_reader_eof_total 6956
telemt_me_idle_close_by_peer_total 6956
telemt_me_route_drop_no_conn_total 1574526
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2805252
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11787
telemt_desync_full_logged_total 3910
telemt_desync_suppressed_total 7877
telemt_desync_frames_bucket_total{bucket="1_2"} 2260
telemt_desync_frames_bucket_total{bucket="3_10"} 4592
telemt_desync_frames_bucket_total{bucket="gt_10"} 4935
telemt_pool_swap_total 49
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 54
telemt_me_writer_removed_unexpected_total 6712
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6447
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 2804955
telemt_user_connections_current{user="hello"} 2486
telemt_user_octets_from_client{user="hello"} 42924008354 (39.98 GB)
telemt_user_octets_to_client{user="hello"} 1055673560098 (983.17 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 985
telemt_user_unique_ips_recent_window{user="hello"} 329
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 55405.0 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3155022
telemt_connections_bad_total 484256
telemt_connections_current 2108
telemt_connections_me_current 2108
telemt_handshake_timeouts_total 50122
telemt_upstream_connect_attempt_total 9053
telemt_upstream_connect_success_total 8988
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7172
telemt_me_reconnect_success_total 6234
telemt_me_reader_eof_total 6561
telemt_me_idle_close_by_peer_total 6560
telemt_me_route_drop_no_conn_total 1986164
telemt_me_route_drop_channel_closed_total 177
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2196598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8104
telemt_desync_full_logged_total 2495
telemt_desync_suppressed_total 5609
telemt_desync_frames_bucket_total{bucket="1_2"} 1997
telemt_desync_frames_bucket_total{bucket="3_10"} 3072
telemt_desync_frames_bucket_total{bucket="gt_10"} 3035
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6298
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6233
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 2191631
telemt_user_connections_current{user="hello"} 2108
telemt_user_octets_from_client{user="hello"} 33252089956 (30.97 GB)
telemt_user_octets_to_client{user="hello"} 861204806492 (802.06 GB)
telemt_user_unique_ips_current{user="hello"} 759
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 55392.4 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2848020
telemt_connections_bad_total 219495
telemt_connections_current 1942
telemt_connections_me_current 1942
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 34267
telemt_upstream_connect_attempt_total 61585
telemt_upstream_connect_success_total 57083
telemt_upstream_connect_fail_total 4502
telemt_upstream_connect_attempts_per_request{bucket="1"} 61585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4502
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9515
telemt_me_reconnect_success_total 6596
telemt_me_reader_eof_total 6877
telemt_me_idle_close_by_peer_total 6876
telemt_me_route_drop_no_conn_total 1941955
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2303294
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8871
telemt_desync_full_logged_total 2835
telemt_desync_suppressed_total 6036
telemt_desync_frames_bucket_total{bucket="1_2"} 2161
telemt_desync_frames_bucket_total{bucket="3_10"} 3241
telemt_desync_frames_bucket_total{bucket="gt_10"} 3469
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7273
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6592
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 677
telemt_user_connections_total{user="hello"} 2349430
telemt_user_connections_current{user="hello"} 1942
telemt_user_octets_from_client{user="hello"} 37350844994 (34.79 GB)
telemt_user_octets_to_client{user="hello"} 692741861419 (645.17 GB)
telemt_user_msgs_from_client{user="hello"} 251914
telemt_user_msgs_to_client{user="hello"} 1773933
telemt_user_unique_ips_current{user="hello"} 732
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 109115.6 (30h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6574997
telemt_connections_bad_total 1151633
telemt_connections_current 2123
telemt_connections_me_current 2123
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 117655
telemt_upstream_connect_attempt_total 129044
telemt_upstream_connect_success_total 95751
telemt_upstream_connect_fail_total 33293
telemt_upstream_connect_attempts_per_request{bucket="1"} 129044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33293
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79665
telemt_me_reconnect_success_total 13989
telemt_me_reader_eof_total 15053
telemt_me_idle_close_by_peer_total 15039
telemt_me_route_drop_no_conn_total 2858800
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4626956
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
telemt_desync_total 20089
telemt_desync_full_logged_total 6392
telemt_desync_suppressed_total 13697
telemt_desync_frames_bucket_total{bucket="1_2"} 3545
telemt_desync_frames_bucket_total{bucket="3_10"} 8314
telemt_desync_frames_bucket_total{bucket="gt_10"} 8230
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 14309
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13964
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 4702030
telemt_user_connections_current{user="hello"} 2123
telemt_user_octets_from_client{user="hello"} 74597782476 (69.47 GB)
telemt_user_octets_to_client{user="hello"} 1834214442828 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 262
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 55355.5 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1243540
telemt_connections_bad_total 94754
telemt_connections_current 642
telemt_connections_me_current 642
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13666
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
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
telemt_me_route_drop_no_conn_total 473203
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
telemt_desync_total 1451
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 899
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
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
telemt_user_connections_total{user="hello"} 1079168
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 8145112771 (7.59 GB)
telemt_user_octets_to_client{user="hello"} 146608501038 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 55357.0 (15h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2214791
telemt_connections_bad_total 140418
telemt_connections_current 2119
telemt_connections_me_current 2119
telemt_handshake_timeouts_total 42151
telemt_upstream_connect_attempt_total 9998
telemt_upstream_connect_success_total 9933
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7216
telemt_me_reconnect_success_total 7168
telemt_me_reader_eof_total 7571
telemt_me_idle_close_by_peer_total 7571
telemt_me_route_drop_no_conn_total 798331
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1877633
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9640
telemt_desync_full_logged_total 3103
telemt_desync_suppressed_total 6537
telemt_desync_frames_bucket_total{bucket="1_2"} 1876
telemt_desync_frames_bucket_total{bucket="3_10"} 3384
telemt_desync_frames_bucket_total{bucket="gt_10"} 4380
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7267
telemt_me_writer_restored_same_endpoint_total 7151
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 1876451
telemt_user_connections_current{user="hello"} 2119
telemt_user_octets_from_client{user="hello"} 38882662340 (36.21 GB)
telemt_user_octets_to_client{user="hello"} 975955276692 (908.93 GB)
telemt_user_unique_ips_current{user="hello"} 748
telemt_user_unique_ips_recent_window{user="hello"} 203
```