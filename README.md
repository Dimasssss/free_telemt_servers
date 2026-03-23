# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 03:23:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 109008.8 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3723653
telemt_connections_bad_total 359573
telemt_connections_current 1066
telemt_connections_me_current 1066
telemt_handshake_timeouts_total 120721
telemt_upstream_connect_attempt_total 40688
telemt_upstream_connect_success_total 40687
telemt_upstream_connect_attempts_per_request{bucket="1"} 40687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1435
telemt_me_reconnect_success_total 635
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 3013235
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3041131
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 778
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 851
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 13066
telemt_desync_full_logged_total 4152
telemt_desync_suppressed_total 8914
telemt_desync_frames_bucket_total{bucket="1_2"} 3464
telemt_desync_frames_bucket_total{bucket="3_10"} 4778
telemt_desync_frames_bucket_total{bucket="gt_10"} 4824
telemt_pool_swap_total 121
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 37230
telemt_me_writer_removed_unexpected_total 629
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34858
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3606
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33568
telemt_me_writer_teardown_success_total{mode="normal"} 37507
telemt_me_writer_teardown_noop_total 37241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.611901
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3030010
telemt_user_connections_current{user="hello"} 1066
telemt_user_octets_from_client{user="hello"} 42938904864 (39.99 GB)
telemt_user_octets_to_client{user="hello"} 825480131248 (768.79 GB)
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 122374.8 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4050024
telemt_connections_bad_total 374414
telemt_connections_current 518
telemt_connections_me_current 518
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101929
telemt_upstream_connect_attempt_total 77011
telemt_upstream_connect_success_total 76090
telemt_upstream_connect_fail_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 76904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 814
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10517
telemt_me_reconnect_success_total 3749
telemt_me_reader_eof_total 3730
telemt_me_idle_close_by_peer_total 3730
telemt_me_route_drop_no_conn_total 3648003
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3216457
telemt_me_endpoint_quarantine_total 990
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 961
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 13123
telemt_desync_full_logged_total 7371
telemt_desync_suppressed_total 5752
telemt_desync_frames_bucket_total{bucket="1_2"} 2984
telemt_desync_frames_bucket_total{bucket="3_10"} 5146
telemt_desync_frames_bucket_total{bucket="gt_10"} 4993
telemt_pool_swap_total 115
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50913
telemt_me_writer_removed_unexpected_total 3655
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47713
telemt_me_writer_teardown_success_total{mode="normal"} 54606
telemt_me_writer_teardown_noop_total 50914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105520
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.689193
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105520
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 265
telemt_me_writer_restored_same_endpoint_total 3322
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 3230938
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 43417154003 (40.44 GB)
telemt_user_octets_to_client{user="hello"} 803556117313 (748.37 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 197234.7 (54h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16456029
telemt_connections_bad_total 1669923
telemt_connections_current 1270
telemt_connections_me_current 1270
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399971
telemt_upstream_connect_attempt_total 88870
telemt_upstream_connect_success_total 88763
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3077
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1585
telemt_me_idle_close_by_peer_total 1583
telemt_me_route_drop_no_conn_total 14064446
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13063348
telemt_me_endpoint_quarantine_total 1327
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1488
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 54291
telemt_desync_full_logged_total 17291
telemt_desync_suppressed_total 37000
telemt_desync_frames_bucket_total{bucket="1_2"} 12110
telemt_desync_frames_bucket_total{bucket="3_10"} 21203
telemt_desync_frames_bucket_total{bucket="gt_10"} 20978
telemt_pool_swap_total 214
telemt_pool_force_close_total 6903
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1072
telemt_me_draining_writers_reap_progress_total 67941
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63023
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61038
telemt_me_writer_teardown_success_total{mode="normal"} 68745
telemt_me_writer_teardown_noop_total 67994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.015479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1072
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1416
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 13063303
telemt_user_connections_current{user="hello"} 1270
telemt_user_octets_from_client{user="hello"} 198065056985 (184.46 GB)
telemt_user_octets_to_client{user="hello"} 3525859731863 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 197236.2 (54h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11996152
telemt_connections_bad_total 1260192
telemt_connections_current 746
telemt_connections_me_current 746
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345871
telemt_upstream_connect_attempt_total 103155
telemt_upstream_connect_success_total 101814
telemt_upstream_connect_fail_total 888
telemt_upstream_connect_attempts_per_request{bucket="1"} 102702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 888
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4551
telemt_me_reconnect_success_total 1950
telemt_me_reader_eof_total 1817
telemt_me_idle_close_by_peer_total 1817
telemt_me_route_drop_no_conn_total 4570106
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8886364
telemt_me_endpoint_quarantine_total 1346
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 39126
telemt_desync_full_logged_total 13180
telemt_desync_suppressed_total 25946
telemt_desync_frames_bucket_total{bucket="1_2"} 9688
telemt_desync_frames_bucket_total{bucket="3_10"} 15031
telemt_desync_frames_bucket_total{bucket="gt_10"} 14407
telemt_pool_swap_total 211
telemt_pool_force_close_total 6251
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66059
telemt_me_writer_removed_unexpected_total 1844
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61947
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59808
telemt_me_writer_teardown_success_total{mode="normal"} 67762
telemt_me_writer_teardown_noop_total 66084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.557422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1668
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8824068
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 218460916204 (203.46 GB)
telemt_user_octets_to_client{user="hello"} 3986350127943 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 197200.3 (54h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11148527
telemt_connections_bad_total 1000132
telemt_connections_current 593
telemt_connections_me_current 593
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346800
telemt_upstream_connect_attempt_total 87584
telemt_upstream_connect_success_total 86018
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5823
telemt_me_reconnect_success_total 2426
telemt_me_reader_eof_total 2174
telemt_me_idle_close_by_peer_total 2173
telemt_me_route_drop_no_conn_total 5348628
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8410842
telemt_me_endpoint_quarantine_total 1385
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1466
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 37
telemt_desync_total 38343
telemt_desync_full_logged_total 12715
telemt_desync_suppressed_total 25628
telemt_desync_frames_bucket_total{bucket="1_2"} 9687
telemt_desync_frames_bucket_total{bucket="3_10"} 14684
telemt_desync_frames_bucket_total{bucket="gt_10"} 13972
telemt_pool_swap_total 206
telemt_pool_force_close_total 6142
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 747
telemt_me_draining_writers_reap_progress_total 66567
telemt_me_writer_removed_unexpected_total 2321
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62279
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5571
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60425
telemt_me_writer_teardown_success_total{mode="normal"} 68823
telemt_me_writer_teardown_noop_total 66638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.879870
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 747
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2113
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8402740
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 193182396495 (179.92 GB)
telemt_user_octets_to_client{user="hello"} 3487549017285 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67480.4 (18h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11390181
telemt_connections_bad_total 672039
telemt_connections_current 1303
telemt_connections_me_current 1303
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 291058
telemt_upstream_connect_attempt_total 61983
telemt_upstream_connect_success_total 58792
telemt_upstream_connect_fail_total 2059
telemt_upstream_connect_attempts_per_request{bucket="1"} 60851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6021
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2059
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7917
telemt_me_reconnect_success_total 1343
telemt_me_reader_eof_total 880
telemt_me_idle_close_by_peer_total 879
telemt_me_route_drop_no_conn_total 25313604
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9442759
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 539
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 16746
telemt_desync_full_logged_total 4597
telemt_desync_suppressed_total 12149
telemt_desync_frames_bucket_total{bucket="1_2"} 3198
telemt_desync_frames_bucket_total{bucket="3_10"} 6831
telemt_desync_frames_bucket_total{bucket="gt_10"} 6717
telemt_pool_swap_total 69
telemt_pool_force_close_total 2193
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 22174
telemt_me_writer_removed_unexpected_total 1232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20514
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19981
telemt_me_writer_teardown_success_total{mode="normal"} 23354
telemt_me_writer_teardown_noop_total 22193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45547
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.064338
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45547
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 9468567
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 88026630966 (81.98 GB)
telemt_user_octets_to_client{user="hello"} 644105281274 (599.87 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 197206.6 (54h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11102261
telemt_connections_bad_total 967963
telemt_connections_current 977
telemt_connections_me_current 977
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244712
telemt_upstream_connect_attempt_total 116385
telemt_upstream_connect_success_total 115192
telemt_upstream_connect_fail_total 1018
telemt_upstream_connect_attempts_per_request{bucket="1"} 116210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1370
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1018
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73208
telemt_me_reconnect_success_total 3169
telemt_me_reader_eof_total 2869
telemt_me_idle_close_by_peer_total 2866
telemt_me_route_drop_no_conn_total 5279279
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8750150
telemt_me_endpoint_quarantine_total 1337
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1494
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 37
telemt_desync_total 46608
telemt_desync_full_logged_total 15998
telemt_desync_suppressed_total 30610
telemt_desync_frames_bucket_total{bucket="1_2"} 9468
telemt_desync_frames_bucket_total{bucket="3_10"} 17847
telemt_desync_frames_bucket_total{bucket="gt_10"} 19293
telemt_pool_swap_total 202
telemt_pool_force_close_total 5860
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 70567
telemt_me_writer_removed_unexpected_total 2888
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7092
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66408
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5111
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64707
telemt_me_writer_teardown_success_total{mode="normal"} 73500
telemt_me_writer_teardown_noop_total 70568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.320855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2672
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8753011
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 196643033217 (183.14 GB)
telemt_user_octets_to_client{user="hello"} 3343988453968 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 134042.9 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11828939
telemt_connections_bad_total 484583
telemt_connections_current 702
telemt_connections_me_current 702
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4791752
telemt_upstream_connect_attempt_total 65127
telemt_upstream_connect_success_total 64658
telemt_upstream_connect_fail_total 456
telemt_upstream_connect_attempts_per_request{bucket="1"} 65114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 456
telemt_me_reconnect_attempts_total 49181
telemt_me_reconnect_success_total 1915
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1590
telemt_me_route_drop_no_conn_total 4107234
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5682971
telemt_me_endpoint_quarantine_total 919
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1032
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31907
telemt_desync_full_logged_total 10913
telemt_desync_suppressed_total 20994
telemt_desync_frames_bucket_total{bucket="1_2"} 6372
telemt_desync_frames_bucket_total{bucket="3_10"} 12589
telemt_desync_frames_bucket_total{bucket="gt_10"} 12946
telemt_pool_swap_total 142
telemt_pool_force_close_total 4067
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 50255
telemt_me_writer_removed_unexpected_total 1635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4041
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47899
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46188
telemt_me_writer_teardown_success_total{mode="normal"} 51940
telemt_me_writer_teardown_noop_total 50262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102202
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.757592
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102202
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 2746
telemt_me_writer_restored_same_endpoint_total 1692
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5675040
telemt_user_connections_current{user="hello"} 702
telemt_user_octets_from_client{user="hello"} 120529565528 (112.25 GB)
telemt_user_octets_to_client{user="hello"} 2209665078730 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 115013.9 (31h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1583672
telemt_connections_bad_total 37003
telemt_connections_current 494
telemt_connections_me_current 494
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32622
telemt_upstream_connect_attempt_total 54469
telemt_upstream_connect_success_total 54300
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 54441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 807
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2369
telemt_me_reconnect_success_total 966
telemt_me_reader_eof_total 957
telemt_me_idle_close_by_peer_total 957
telemt_me_route_drop_no_conn_total 531556
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1407995
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 952
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 9887
telemt_desync_full_logged_total 2794
telemt_desync_suppressed_total 7093
telemt_desync_frames_bucket_total{bucket="1_2"} 3079
telemt_desync_frames_bucket_total{bucket="3_10"} 3736
telemt_desync_frames_bucket_total{bucket="gt_10"} 3072
telemt_pool_swap_total 124
telemt_pool_force_close_total 3122
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 46329
telemt_me_writer_removed_unexpected_total 922
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3507
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43786
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3034
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43207
telemt_me_writer_teardown_success_total{mode="normal"} 47293
telemt_me_writer_teardown_noop_total 46333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93626
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.497724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93626
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1403718
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 26554129029 (24.73 GB)
telemt_user_octets_to_client{user="hello"} 590683483271 (550.12 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 197211.3 (54h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13420186
telemt_connections_bad_total 1626999
telemt_connections_current 780
telemt_connections_me_current 780
telemt_handshake_timeouts_total 391647
telemt_upstream_connect_attempt_total 79045
telemt_upstream_connect_success_total 78689
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 78909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39708
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3085
telemt_me_reconnect_success_total 1560
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 4494557
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10106530
telemt_me_endpoint_quarantine_total 1446
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1495
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 42403
telemt_desync_full_logged_total 13851
telemt_desync_suppressed_total 28552
telemt_desync_frames_bucket_total{bucket="1_2"} 10322
telemt_desync_frames_bucket_total{bucket="3_10"} 15574
telemt_desync_frames_bucket_total{bucket="gt_10"} 16507
telemt_pool_swap_total 219
telemt_pool_force_close_total 5726
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 686
telemt_me_draining_writers_reap_progress_total 71523
telemt_me_writer_removed_unexpected_total 1481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67519
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65797
telemt_me_writer_teardown_success_total{mode="normal"} 73059
telemt_me_writer_teardown_noop_total 71525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144584
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.858554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144584
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 686
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1373
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10073157
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 195310760872 (181.90 GB)
telemt_user_octets_to_client{user="hello"} 4479693063320 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 197207.8 (54h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11730940
telemt_connections_bad_total 1373284
telemt_connections_current 716
telemt_connections_me_current 716
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 314270
telemt_upstream_connect_attempt_total 106721
telemt_upstream_connect_success_total 105800
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 106513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10763
telemt_me_reconnect_success_total 2672
telemt_me_reader_eof_total 2481
telemt_me_idle_close_by_peer_total 2480
telemt_me_seq_mismatch_total 103
telemt_me_route_drop_no_conn_total 5662738
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9025176
telemt_me_endpoint_quarantine_total 1612
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1498
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 40
telemt_desync_total 42124
telemt_desync_full_logged_total 13564
telemt_desync_suppressed_total 28560
telemt_desync_frames_bucket_total{bucket="1_2"} 10946
telemt_desync_frames_bucket_total{bucket="3_10"} 15480
telemt_desync_frames_bucket_total{bucket="gt_10"} 15698
telemt_pool_swap_total 208
telemt_pool_force_close_total 5495
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71705
telemt_me_writer_removed_unexpected_total 2516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67397
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5024
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66210
telemt_me_writer_teardown_success_total{mode="normal"} 74318
telemt_me_writer_teardown_noop_total 71710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146028
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.574086
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146028
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 419
telemt_me_writer_restored_same_endpoint_total 2139
telemt_me_writer_restored_fallback_total 139
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9029734
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 157950766092 (147.10 GB)
telemt_user_octets_to_client{user="hello"} 3522377802474 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 81
```