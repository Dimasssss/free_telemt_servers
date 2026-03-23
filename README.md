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

# Server Metrics 2026-03-23 00:35:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 98936.8 (27h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3471690
telemt_connections_bad_total 300135
telemt_connections_current 841
telemt_connections_me_current 841
telemt_handshake_timeouts_total 108434
telemt_upstream_connect_attempt_total 36639
telemt_upstream_connect_success_total 36638
telemt_upstream_connect_attempts_per_request{bucket="1"} 36638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1384
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 2978471
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2874043
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 682
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 768
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
telemt_desync_total 12372
telemt_desync_full_logged_total 3871
telemt_desync_suppressed_total 8501
telemt_desync_frames_bucket_total{bucket="1_2"} 3343
telemt_desync_frames_bucket_total{bucket="3_10"} 4498
telemt_desync_frames_bucket_total{bucket="gt_10"} 4531
telemt_pool_swap_total 109
telemt_pool_force_close_total 3375
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 33550
telemt_me_writer_removed_unexpected_total 585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31347
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30175
telemt_me_writer_teardown_success_total{mode="normal"} 33782
telemt_me_writer_teardown_noop_total 33561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.109641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 528
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2863236
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 40895367012 (38.09 GB)
telemt_user_octets_to_client{user="hello"} 784109315700 (730.26 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 112303.2 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3988891
telemt_connections_bad_total 364992
telemt_connections_current 394
telemt_connections_me_current 394
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100463
telemt_upstream_connect_attempt_total 69777
telemt_upstream_connect_success_total 68942
telemt_upstream_connect_fail_total 742
telemt_upstream_connect_attempts_per_request{bucket="1"} 69684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 742
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9916
telemt_me_reconnect_success_total 3582
telemt_me_reader_eof_total 3579
telemt_me_idle_close_by_peer_total 3579
telemt_me_route_drop_no_conn_total 3639967
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3171488
telemt_me_endpoint_quarantine_total 877
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 874
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 49
telemt_desync_total 12938
telemt_desync_full_logged_total 7251
telemt_desync_suppressed_total 5687
telemt_desync_frames_bucket_total{bucket="1_2"} 2937
telemt_desync_frames_bucket_total{bucket="3_10"} 5072
telemt_desync_frames_bucket_total{bucket="gt_10"} 4929
telemt_pool_swap_total 104
telemt_pool_force_close_total 3031
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 45931
telemt_me_writer_removed_unexpected_total 3511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42900
telemt_me_writer_teardown_success_total{mode="normal"} 49473
telemt_me_writer_teardown_noop_total 45932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95405
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.581350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95405
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 3208
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 3184326
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 42944122819 (39.99 GB)
telemt_user_octets_to_client{user="hello"} 789447805159 (735.23 GB)
telemt_user_msgs_from_client{user="hello"} 48526
telemt_user_msgs_to_client{user="hello"} 183196
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 187163.1 (51h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16311152
telemt_connections_bad_total 1644132
telemt_connections_current 848
telemt_connections_me_current 848
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396985
telemt_upstream_connect_attempt_total 83655
telemt_upstream_connect_success_total 83551
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 83568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1714
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2982
telemt_me_reconnect_success_total 1560
telemt_me_reader_eof_total 1507
telemt_me_idle_close_by_peer_total 1505
telemt_me_route_drop_no_conn_total 14042542
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12956043
telemt_me_endpoint_quarantine_total 1227
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1404
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53695
telemt_desync_full_logged_total 17041
telemt_desync_suppressed_total 36654
telemt_desync_frames_bucket_total{bucket="1_2"} 11958
telemt_desync_frames_bucket_total{bucket="3_10"} 20944
telemt_desync_frames_bucket_total{bucket="gt_10"} 20793
telemt_pool_swap_total 202
telemt_pool_force_close_total 6661
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1057
telemt_me_draining_writers_reap_progress_total 63171
telemt_me_writer_removed_unexpected_total 1452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58480
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6191
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56510
telemt_me_writer_teardown_success_total{mode="normal"} 63897
telemt_me_writer_teardown_noop_total 63224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.578603
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1057
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1349
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12956101
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 190967418925 (177.85 GB)
telemt_user_octets_to_client{user="hello"} 3484540983059 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 187164.4 (51h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11853707
telemt_connections_bad_total 1228923
telemt_connections_current 579
telemt_connections_me_current 579
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344495
telemt_upstream_connect_attempt_total 98013
telemt_upstream_connect_success_total 96694
telemt_upstream_connect_fail_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 97560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 866
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4397
telemt_me_reconnect_success_total 1864
telemt_me_reader_eof_total 1729
telemt_me_idle_close_by_peer_total 1729
telemt_me_route_drop_no_conn_total 4552903
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8802230
telemt_me_endpoint_quarantine_total 1233
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1425
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38713
telemt_desync_full_logged_total 13033
telemt_desync_suppressed_total 25680
telemt_desync_frames_bucket_total{bucket="1_2"} 9592
telemt_desync_frames_bucket_total{bucket="3_10"} 14869
telemt_desync_frames_bucket_total{bucket="gt_10"} 14252
telemt_pool_swap_total 199
telemt_pool_force_close_total 6022
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 61384
telemt_me_writer_removed_unexpected_total 1760
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5511
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57488
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5510
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55362
telemt_me_writer_teardown_success_total{mode="normal"} 62999
telemt_me_writer_teardown_noop_total 61409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.394167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1592
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8739998
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 217704472820 (202.75 GB)
telemt_user_octets_to_client{user="hello"} 3957882594107 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 187128.5 (51h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11038245
telemt_connections_bad_total 972108
telemt_connections_current 423
telemt_connections_me_current 423
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345499
telemt_upstream_connect_attempt_total 82326
telemt_upstream_connect_success_total 80768
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 80973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5714
telemt_me_reconnect_success_total 2355
telemt_me_reader_eof_total 2099
telemt_me_idle_close_by_peer_total 2098
telemt_me_route_drop_no_conn_total 5334807
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8344659
telemt_me_endpoint_quarantine_total 1308
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1383
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 49
telemt_desync_total 38064
telemt_desync_full_logged_total 12620
telemt_desync_suppressed_total 25444
telemt_desync_frames_bucket_total{bucket="1_2"} 9612
telemt_desync_frames_bucket_total{bucket="3_10"} 14559
telemt_desync_frames_bucket_total{bucket="gt_10"} 13893
telemt_pool_swap_total 195
telemt_pool_force_close_total 5922
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 738
telemt_me_draining_writers_reap_progress_total 61786
telemt_me_writer_removed_unexpected_total 2249
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5351
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55864
telemt_me_writer_teardown_success_total{mode="normal"} 63967
telemt_me_writer_teardown_noop_total 61857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.688589
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 738
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8336629
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 192597506643 (179.37 GB)
telemt_user_octets_to_client{user="hello"} 3465462700525 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 57408.1 (15h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11212052
telemt_connections_bad_total 668603
telemt_connections_current 964
telemt_connections_me_current 964
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 267977
telemt_upstream_connect_attempt_total 56214
telemt_upstream_connect_success_total 53343
telemt_upstream_connect_fail_total 1907
telemt_upstream_connect_attempts_per_request{bucket="1"} 55250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1907
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7479
telemt_me_reconnect_success_total 1177
telemt_me_reader_eof_total 750
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 25286415
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9307494
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 453
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 16279
telemt_desync_full_logged_total 4426
telemt_desync_suppressed_total 11853
telemt_desync_frames_bucket_total{bucket="1_2"} 3087
telemt_desync_frames_bucket_total{bucket="3_10"} 6622
telemt_desync_frames_bucket_total{bucket="gt_10"} 6570
telemt_pool_swap_total 59
telemt_pool_force_close_total 1961
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 17780
telemt_me_writer_removed_unexpected_total 1065
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2405
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15819
telemt_me_writer_teardown_success_total{mode="normal"} 18787
telemt_me_writer_teardown_noop_total 17799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.615661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9332828
telemt_user_connections_current{user="hello"} 964
telemt_user_octets_from_client{user="hello"} 86959251638 (80.99 GB)
telemt_user_octets_to_client{user="hello"} 601486626325 (560.18 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 187134.8 (51h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10972112
telemt_connections_bad_total 942660
telemt_connections_current 694
telemt_connections_me_current 694
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241882
telemt_upstream_connect_attempt_total 111238
telemt_upstream_connect_success_total 110092
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 111065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72864
telemt_me_reconnect_success_total 3059
telemt_me_reader_eof_total 2747
telemt_me_idle_close_by_peer_total 2745
telemt_me_route_drop_no_conn_total 5258570
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8660932
telemt_me_endpoint_quarantine_total 1254
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1411
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
telemt_me_writers_active_current 47
telemt_desync_total 46183
telemt_desync_full_logged_total 15809
telemt_desync_suppressed_total 30374
telemt_desync_frames_bucket_total{bucket="1_2"} 9385
telemt_desync_frames_bucket_total{bucket="3_10"} 17679
telemt_desync_frames_bucket_total{bucket="gt_10"} 19119
telemt_pool_swap_total 191
telemt_pool_force_close_total 5627
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65962
telemt_me_writer_removed_unexpected_total 2776
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6778
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61995
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60335
telemt_me_writer_teardown_success_total{mode="normal"} 68773
telemt_me_writer_teardown_noop_total 65963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134736
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.229287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134736
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2583
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8663963
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 194460898217 (181.11 GB)
telemt_user_octets_to_client{user="hello"} 3308582988884 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 123971.1 (34h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11671452
telemt_connections_bad_total 477089
telemt_connections_current 545
telemt_connections_me_current 545
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759987
telemt_upstream_connect_attempt_total 59479
telemt_upstream_connect_success_total 59047
telemt_upstream_connect_fail_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 59468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 421
telemt_me_reconnect_attempts_total 48874
telemt_me_reconnect_success_total 1803
telemt_me_reader_eof_total 1474
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 4085113
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5608160
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 949
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31505
telemt_desync_full_logged_total 10737
telemt_desync_suppressed_total 20768
telemt_desync_frames_bucket_total{bucket="1_2"} 6271
telemt_desync_frames_bucket_total{bucket="3_10"} 12426
telemt_desync_frames_bucket_total{bucket="gt_10"} 12808
telemt_pool_swap_total 131
telemt_pool_force_close_total 3857
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 45123
telemt_me_writer_removed_unexpected_total 1525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3741
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42950
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41266
telemt_me_writer_teardown_success_total{mode="normal"} 46691
telemt_me_writer_teardown_noop_total 45130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91821
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.681904
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91821
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2735
telemt_me_writer_restored_same_endpoint_total 1600
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5600724
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 119007797160 (110.83 GB)
telemt_user_octets_to_client{user="hello"} 2166638196686 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 104941.5 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1510358
telemt_connections_bad_total 36693
telemt_connections_current 410
telemt_connections_me_current 410
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30305
telemt_upstream_connect_attempt_total 49251
telemt_upstream_connect_success_total 49095
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 49223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 786
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2210
telemt_me_reconnect_success_total 893
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 879
telemt_me_route_drop_no_conn_total 515905
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1342078
telemt_me_endpoint_quarantine_total 854
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 868
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 47
telemt_desync_total 8787
telemt_desync_full_logged_total 2591
telemt_desync_suppressed_total 6196
telemt_desync_frames_bucket_total{bucket="1_2"} 2410
telemt_desync_frames_bucket_total{bucket="3_10"} 3367
telemt_desync_frames_bucket_total{bucket="gt_10"} 3010
telemt_pool_swap_total 113
telemt_pool_force_close_total 2910
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 41570
telemt_me_writer_removed_unexpected_total 847
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2822
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38660
telemt_me_writer_teardown_success_total{mode="normal"} 42456
telemt_me_writer_teardown_noop_total 41574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.225423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1337892
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 25858974693 (24.08 GB)
telemt_user_octets_to_client{user="hello"} 572699916395 (533.37 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 187139.6 (51h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13310396
telemt_connections_bad_total 1600250
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 388343
telemt_upstream_connect_attempt_total 73173
telemt_upstream_connect_success_total 72826
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 73037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2930
telemt_me_reconnect_success_total 1466
telemt_me_reader_eof_total 1451
telemt_me_idle_close_by_peer_total 1451
telemt_me_route_drop_no_conn_total 4480944
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10035854
telemt_me_endpoint_quarantine_total 1312
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1412
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
telemt_me_writers_active_current 48
telemt_desync_total 42024
telemt_desync_full_logged_total 13723
telemt_desync_suppressed_total 28301
telemt_desync_frames_bucket_total{bucket="1_2"} 10156
telemt_desync_frames_bucket_total{bucket="3_10"} 15444
telemt_desync_frames_bucket_total{bucket="gt_10"} 16424
telemt_pool_swap_total 207
telemt_pool_force_close_total 5550
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 66087
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62298
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60537
telemt_me_writer_teardown_success_total{mode="normal"} 67528
telemt_me_writer_teardown_noop_total 66089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.750062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1284
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10002574
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 194622600320 (181.26 GB)
telemt_user_octets_to_client{user="hello"} 4435693091096 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 187136.1 (51h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11616953
telemt_connections_bad_total 1351126
telemt_connections_current 568
telemt_connections_me_current 568
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310651
telemt_upstream_connect_attempt_total 99913
telemt_upstream_connect_success_total 99032
telemt_upstream_connect_fail_total 673
telemt_upstream_connect_attempts_per_request{bucket="1"} 99705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 673
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10359
telemt_me_reconnect_success_total 2552
telemt_me_reader_eof_total 2367
telemt_me_idle_close_by_peer_total 2366
telemt_me_seq_mismatch_total 96
telemt_me_route_drop_no_conn_total 5648253
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8946124
telemt_me_endpoint_quarantine_total 1498
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1414
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_active_current 45
telemt_desync_total 41724
telemt_desync_full_logged_total 13428
telemt_desync_suppressed_total 28296
telemt_desync_frames_bucket_total{bucket="1_2"} 10756
telemt_desync_frames_bucket_total{bucket="3_10"} 15344
telemt_desync_frames_bucket_total{bucket="gt_10"} 15624
telemt_pool_swap_total 197
telemt_pool_force_close_total 5343
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 66160
telemt_me_writer_removed_unexpected_total 2409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6583
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62069
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60817
telemt_me_writer_teardown_success_total{mode="normal"} 68652
telemt_me_writer_teardown_noop_total 66165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134817
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.451344
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134817
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 404
telemt_me_writer_restored_same_endpoint_total 2059
telemt_me_writer_restored_fallback_total 131
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 8949969
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 157221717141 (146.42 GB)
telemt_user_octets_to_client{user="hello"} 3484002293267 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 62
```