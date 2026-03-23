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

# Server Metrics 2026-03-23 03:33:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 109620.7 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3740793
telemt_connections_bad_total 362880
telemt_connections_current 1204
telemt_connections_me_current 1204
telemt_handshake_timeouts_total 122074
telemt_upstream_connect_attempt_total 40897
telemt_upstream_connect_success_total 40896
telemt_upstream_connect_attempts_per_request{bucket="1"} 40896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1436
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 653
telemt_me_idle_close_by_peer_total 653
telemt_me_route_drop_no_conn_total 3015765
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3053069
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 778
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 856
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
telemt_me_writers_active_current 44
telemt_desync_total 13087
telemt_desync_full_logged_total 4158
telemt_desync_suppressed_total 8929
telemt_desync_frames_bucket_total{bucket="1_2"} 3464
telemt_desync_frames_bucket_total{bucket="3_10"} 4791
telemt_desync_frames_bucket_total{bucket="gt_10"} 4832
telemt_pool_swap_total 121
telemt_pool_force_close_total 3689
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 37452
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35068
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33763
telemt_me_writer_teardown_success_total{mode="normal"} 37730
telemt_me_writer_teardown_noop_total 37463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75193
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.811645
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75193
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3041931
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 43052234000 (40.10 GB)
telemt_user_octets_to_client{user="hello"} 827906284436 (771.05 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 122986.3 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4057946
telemt_connections_bad_total 376667
telemt_connections_current 537
telemt_connections_me_current 537
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102323
telemt_upstream_connect_attempt_total 77353
telemt_upstream_connect_success_total 76428
telemt_upstream_connect_fail_total 818
telemt_upstream_connect_attempts_per_request{bucket="1"} 77246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 818
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10526
telemt_me_reconnect_success_total 3757
telemt_me_reader_eof_total 3739
telemt_me_idle_close_by_peer_total 3739
telemt_me_route_drop_no_conn_total 3649089
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3221545
telemt_me_endpoint_quarantine_total 995
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 968
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
telemt_me_writers_active_current 44
telemt_desync_total 13150
telemt_desync_full_logged_total 7391
telemt_desync_suppressed_total 5759
telemt_desync_frames_bucket_total{bucket="1_2"} 2988
telemt_desync_frames_bucket_total{bucket="3_10"} 5158
telemt_desync_frames_bucket_total{bucket="gt_10"} 5004
telemt_pool_swap_total 116
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 51213
telemt_me_writer_removed_unexpected_total 3663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6565
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48350
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47990
telemt_me_writer_teardown_success_total{mode="normal"} 54915
telemt_me_writer_teardown_noop_total 51214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.694205
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 265
telemt_me_writer_restored_same_endpoint_total 3330
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 3236020
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 43488878607 (40.50 GB)
telemt_user_octets_to_client{user="hello"} 804973488649 (749.69 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 197846.2 (54h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16467310
telemt_connections_bad_total 1670075
telemt_connections_current 1177
telemt_connections_me_current 1177
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 400494
telemt_upstream_connect_attempt_total 89147
telemt_upstream_connect_success_total 89040
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3080
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1588
telemt_me_route_drop_no_conn_total 14066814
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13073725
telemt_me_endpoint_quarantine_total 1327
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1494
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
telemt_me_writers_active_current 45
telemt_desync_total 54368
telemt_desync_full_logged_total 17322
telemt_desync_suppressed_total 37046
telemt_desync_frames_bucket_total{bucket="1_2"} 12117
telemt_desync_frames_bucket_total{bucket="3_10"} 21238
telemt_desync_frames_bucket_total{bucket="gt_10"} 21013
telemt_pool_swap_total 214
telemt_pool_force_close_total 6925
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1073
telemt_me_draining_writers_reap_progress_total 68212
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5739
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63282
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6455
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61287
telemt_me_writer_teardown_success_total{mode="normal"} 69021
telemt_me_writer_teardown_noop_total 68265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.028755
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137286
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1073
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 13073700
telemt_user_connections_current{user="hello"} 1177
telemt_user_octets_from_client{user="hello"} 198206065997 (184.59 GB)
telemt_user_octets_to_client{user="hello"} 3530260797131 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 197847.4 (54h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12007857
telemt_connections_bad_total 1263288
telemt_connections_current 737
telemt_connections_me_current 737
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346135
telemt_upstream_connect_attempt_total 103418
telemt_upstream_connect_success_total 102077
telemt_upstream_connect_fail_total 888
telemt_upstream_connect_attempts_per_request{bucket="1"} 102965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43678
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 888
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4554
telemt_me_reconnect_success_total 1952
telemt_me_reader_eof_total 1819
telemt_me_idle_close_by_peer_total 1819
telemt_me_route_drop_no_conn_total 4571581
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8892941
telemt_me_endpoint_quarantine_total 1347
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1514
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
telemt_desync_total 39129
telemt_desync_full_logged_total 13183
telemt_desync_suppressed_total 25946
telemt_desync_frames_bucket_total{bucket="1_2"} 9688
telemt_desync_frames_bucket_total{bucket="3_10"} 15033
telemt_desync_frames_bucket_total{bucket="gt_10"} 14408
telemt_pool_swap_total 211
telemt_pool_force_close_total 6271
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66318
telemt_me_writer_removed_unexpected_total 1846
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5829
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62194
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60047
telemt_me_writer_teardown_success_total{mode="normal"} 68023
telemt_me_writer_teardown_noop_total 66343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.562251
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1670
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8830641
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 218519135220 (203.51 GB)
telemt_user_octets_to_client{user="hello"} 3988156932311 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 197811.4 (54h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11158018
telemt_connections_bad_total 1002056
telemt_connections_current 672
telemt_connections_me_current 672
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 347185
telemt_upstream_connect_attempt_total 87885
telemt_upstream_connect_success_total 86319
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5828
telemt_me_reconnect_success_total 2433
telemt_me_reader_eof_total 2180
telemt_me_idle_close_by_peer_total 2179
telemt_me_route_drop_no_conn_total 5350049
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8416478
telemt_me_endpoint_quarantine_total 1388
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1474
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_me_writers_active_current 46
telemt_desync_total 38363
telemt_desync_full_logged_total 12721
telemt_desync_suppressed_total 25642
telemt_desync_frames_bucket_total{bucket="1_2"} 9690
telemt_desync_frames_bucket_total{bucket="3_10"} 14695
telemt_desync_frames_bucket_total{bucket="gt_10"} 13978
telemt_pool_swap_total 207
telemt_pool_force_close_total 6166
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 751
telemt_me_draining_writers_reap_progress_total 66873
telemt_me_writer_removed_unexpected_total 2326
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62564
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60707
telemt_me_writer_teardown_success_total{mode="normal"} 69135
telemt_me_writer_teardown_noop_total 66944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.891751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 751
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2118
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8408369
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 193221892131 (179.95 GB)
telemt_user_octets_to_client{user="hello"} 3490906064077 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 68091.9 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11406849
telemt_connections_bad_total 673219
telemt_connections_current 1335
telemt_connections_me_current 1335
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 292254
telemt_upstream_connect_attempt_total 63191
telemt_upstream_connect_success_total 59820
telemt_upstream_connect_fail_total 2197
telemt_upstream_connect_attempts_per_request{bucket="1"} 62017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2197
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8091
telemt_me_reconnect_success_total 1409
telemt_me_reader_eof_total 895
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 25315824
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9455410
telemt_me_endpoint_quarantine_total 526
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 547
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
telemt_me_writers_active_current 43
telemt_desync_total 16779
telemt_desync_full_logged_total 4609
telemt_desync_suppressed_total 12170
telemt_desync_frames_bucket_total{bucket="1_2"} 3212
telemt_desync_frames_bucket_total{bucket="3_10"} 6844
telemt_desync_frames_bucket_total{bucket="gt_10"} 6723
telemt_pool_swap_total 70
telemt_pool_force_close_total 2211
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 503
telemt_me_draining_writers_reap_progress_total 22389
telemt_me_writer_removed_unexpected_total 1292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20709
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20178
telemt_me_writer_teardown_success_total{mode="normal"} 23629
telemt_me_writer_teardown_noop_total 22408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46037
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.117950
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46037
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 503
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 910
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 367
telemt_user_connections_total{user="hello"} 9481934
telemt_user_connections_current{user="hello"} 1335
telemt_user_octets_from_client{user="hello"} 88141866478 (82.09 GB)
telemt_user_octets_to_client{user="hello"} 649449766553 (604.85 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 197818.0 (54h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11113765
telemt_connections_bad_total 970463
telemt_connections_current 994
telemt_connections_me_current 994
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244872
telemt_upstream_connect_attempt_total 116664
telemt_upstream_connect_success_total 115471
telemt_upstream_connect_fail_total 1018
telemt_upstream_connect_attempts_per_request{bucket="1"} 116489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1018
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73218
telemt_me_reconnect_success_total 3179
telemt_me_reader_eof_total 2877
telemt_me_idle_close_by_peer_total 2874
telemt_me_route_drop_no_conn_total 5281425
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8758401
telemt_me_endpoint_quarantine_total 1344
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1502
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 46642
telemt_desync_full_logged_total 16012
telemt_desync_suppressed_total 30630
telemt_desync_frames_bucket_total{bucket="1_2"} 9476
telemt_desync_frames_bucket_total{bucket="3_10"} 17864
telemt_desync_frames_bucket_total{bucket="gt_10"} 19302
telemt_pool_swap_total 203
telemt_pool_force_close_total 5887
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 70854
telemt_me_writer_removed_unexpected_total 2896
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5138
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64967
telemt_me_writer_teardown_success_total{mode="normal"} 73795
telemt_me_writer_teardown_noop_total 70855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144650
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.325342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144650
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8761253
telemt_user_connections_current{user="hello"} 994
telemt_user_octets_from_client{user="hello"} 196743549237 (183.23 GB)
telemt_user_octets_to_client{user="hello"} 3349221333068 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 134654.3 (37h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11844037
telemt_connections_bad_total 485459
telemt_connections_current 764
telemt_connections_me_current 764
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4795903
telemt_upstream_connect_attempt_total 65448
telemt_upstream_connect_success_total 64975
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 65435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_reconnect_attempts_total 49201
telemt_me_reconnect_success_total 1919
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 4108751
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5690300
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1039
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31933
telemt_desync_full_logged_total 10922
telemt_desync_suppressed_total 21011
telemt_desync_frames_bucket_total{bucket="1_2"} 6380
telemt_desync_frames_bucket_total{bucket="3_10"} 12597
telemt_desync_frames_bucket_total{bucket="gt_10"} 12956
telemt_pool_swap_total 143
telemt_pool_force_close_total 4087
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 50562
telemt_me_writer_removed_unexpected_total 1640
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48190
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3643
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46475
telemt_me_writer_teardown_success_total{mode="normal"} 52253
telemt_me_writer_teardown_noop_total 50569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102822
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.759852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102822
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 2747
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5682365
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 120589659580 (112.31 GB)
telemt_user_octets_to_client{user="hello"} 2212305621090 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 115625.2 (32h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1590571
telemt_connections_bad_total 37016
telemt_connections_current 583
telemt_connections_me_current 583
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32710
telemt_upstream_connect_attempt_total 54772
telemt_upstream_connect_success_total 54602
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 54744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2370
telemt_me_reconnect_success_total 967
telemt_me_reader_eof_total 959
telemt_me_idle_close_by_peer_total 959
telemt_me_route_drop_no_conn_total 533201
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414046
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 958
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9919
telemt_desync_full_logged_total 2803
telemt_desync_suppressed_total 7116
telemt_desync_frames_bucket_total{bucket="1_2"} 3098
telemt_desync_frames_bucket_total{bucket="3_10"} 3749
telemt_desync_frames_bucket_total{bucket="gt_10"} 3072
telemt_pool_swap_total 125
telemt_pool_force_close_total 3148
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 46605
telemt_me_writer_removed_unexpected_total 923
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3060
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43457
telemt_me_writer_teardown_success_total{mode="normal"} 47571
telemt_me_writer_teardown_noop_total 46609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94180
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.505638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94180
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1409745
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 26602381061 (24.78 GB)
telemt_user_octets_to_client{user="hello"} 592384095131 (551.70 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 197822.6 (54h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13427233
telemt_connections_bad_total 1627141
telemt_connections_current 943
telemt_connections_me_current 943
telemt_handshake_timeouts_total 391866
telemt_upstream_connect_attempt_total 79356
telemt_upstream_connect_success_total 79000
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 79220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39857
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3089
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 4495928
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10113064
telemt_me_endpoint_quarantine_total 1448
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1501
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
telemt_me_writers_active_current 45
telemt_desync_total 42443
telemt_desync_full_logged_total 13863
telemt_desync_suppressed_total 28580
telemt_desync_frames_bucket_total{bucket="1_2"} 10333
telemt_desync_frames_bucket_total{bucket="3_10"} 15590
telemt_desync_frames_bucket_total{bucket="gt_10"} 16520
telemt_pool_swap_total 219
telemt_pool_force_close_total 5746
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 71833
telemt_me_writer_removed_unexpected_total 1485
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5556
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67818
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5572
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66087
telemt_me_writer_teardown_success_total{mode="normal"} 73374
telemt_me_writer_teardown_noop_total 71835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145209
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.863278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145209
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1377
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10079685
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 195402413496 (181.98 GB)
telemt_user_octets_to_client{user="hello"} 4483175810140 (4.08 TB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 197819.1 (54h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11741356
telemt_connections_bad_total 1376536
telemt_connections_current 680
telemt_connections_me_current 680
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 314718
telemt_upstream_connect_attempt_total 107032
telemt_upstream_connect_success_total 106111
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 106824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10807
telemt_me_reconnect_success_total 2678
telemt_me_reader_eof_total 2486
telemt_me_idle_close_by_peer_total 2485
telemt_me_seq_mismatch_total 103
telemt_me_route_drop_no_conn_total 5664176
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9031703
telemt_me_endpoint_quarantine_total 1620
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1505
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42134
telemt_desync_full_logged_total 13568
telemt_desync_suppressed_total 28566
telemt_desync_frames_bucket_total{bucket="1_2"} 10948
telemt_desync_frames_bucket_total{bucket="3_10"} 15483
telemt_desync_frames_bucket_total{bucket="gt_10"} 15703
telemt_pool_swap_total 209
telemt_pool_force_close_total 5511
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 72028
telemt_me_writer_removed_unexpected_total 2521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67713
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66517
telemt_me_writer_teardown_success_total{mode="normal"} 74646
telemt_me_writer_teardown_noop_total 72033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.586753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 421
telemt_me_writer_restored_same_endpoint_total 2142
telemt_me_writer_restored_fallback_total 139
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 9036252
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 158023039424 (147.17 GB)
telemt_user_octets_to_client{user="hello"} 3525646438886 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 82
```