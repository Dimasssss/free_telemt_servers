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

# Server Metrics 2026-03-23 02:57:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 107482.2 (29h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3677325
telemt_connections_bad_total 350942
telemt_connections_current 1030
telemt_connections_me_current 1030
telemt_handshake_timeouts_total 117914
telemt_upstream_connect_attempt_total 40096
telemt_upstream_connect_success_total 40095
telemt_upstream_connect_attempts_per_request{bucket="1"} 40095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1425
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 3005888
telemt_me_route_drop_channel_closed_total 1235
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3008083
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 761
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 841
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
telemt_me_writers_active_current 48
telemt_desync_total 12934
telemt_desync_full_logged_total 4107
telemt_desync_suppressed_total 8827
telemt_desync_frames_bucket_total{bucket="1_2"} 3433
telemt_desync_frames_bucket_total{bucket="3_10"} 4725
telemt_desync_frames_bucket_total{bucket="gt_10"} 4776
telemt_pool_swap_total 119
telemt_pool_force_close_total 3636
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 36712
telemt_me_writer_removed_unexpected_total 621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3580
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33076
telemt_me_writer_teardown_success_total{mode="normal"} 36982
telemt_me_writer_teardown_noop_total 36723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.517368
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2996975
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 42704502980 (39.77 GB)
telemt_user_octets_to_client{user="hello"} 817994255616 (761.82 GB)
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 120848.4 (33h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4035523
telemt_connections_bad_total 372413
telemt_connections_current 252
telemt_connections_me_current 252
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101489
telemt_upstream_connect_attempt_total 75076
telemt_upstream_connect_success_total 74161
telemt_upstream_connect_fail_total 808
telemt_upstream_connect_attempts_per_request{bucket="1"} 74969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 808
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10419
telemt_me_reconnect_success_total 3725
telemt_me_reader_eof_total 3709
telemt_me_idle_close_by_peer_total 3709
telemt_me_route_drop_no_conn_total 3646029
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3206111
telemt_me_endpoint_quarantine_total 975
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 950
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
telemt_desync_total 13074
telemt_desync_full_logged_total 7344
telemt_desync_suppressed_total 5730
telemt_desync_frames_bucket_total{bucket="1_2"} 2966
telemt_desync_frames_bucket_total{bucket="3_10"} 5132
telemt_desync_frames_bucket_total{bucket="gt_10"} 4976
telemt_pool_swap_total 114
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50191
telemt_me_writer_removed_unexpected_total 3636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6477
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46991
telemt_me_writer_teardown_success_total{mode="normal"} 53863
telemt_me_writer_teardown_noop_total 50192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104055
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.675638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104055
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3306
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3219463
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 43331605630 (40.36 GB)
telemt_user_octets_to_client{user="hello"} 799367390422 (744.47 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 195708.2 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16429642
telemt_connections_bad_total 1667765
telemt_connections_current 990
telemt_connections_me_current 990
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399393
telemt_upstream_connect_attempt_total 88150
telemt_upstream_connect_success_total 88043
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3054
telemt_me_reconnect_success_total 1628
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1576
telemt_me_route_drop_no_conn_total 14059222
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13041817
telemt_me_endpoint_quarantine_total 1315
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1478
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
telemt_me_writers_active_current 46
telemt_desync_total 54134
telemt_desync_full_logged_total 17248
telemt_desync_suppressed_total 36886
telemt_desync_frames_bucket_total{bucket="1_2"} 12074
telemt_desync_frames_bucket_total{bucket="3_10"} 21147
telemt_desync_frames_bucket_total{bucket="gt_10"} 20913
telemt_pool_swap_total 212
telemt_pool_force_close_total 6877
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1070
telemt_me_draining_writers_reap_progress_total 67292
telemt_me_writer_removed_unexpected_total 1516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62405
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60415
telemt_me_writer_teardown_success_total{mode="normal"} 68089
telemt_me_writer_teardown_noop_total 67345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135434
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.977330
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135434
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1070
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1410
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 13041780
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 197829503061 (184.24 GB)
telemt_user_octets_to_client{user="hello"} 3517917921879 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 195709.6 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11969223
telemt_connections_bad_total 1253822
telemt_connections_current 686
telemt_connections_me_current 686
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345400
telemt_upstream_connect_attempt_total 102413
telemt_upstream_connect_success_total 101077
telemt_upstream_connect_fail_total 883
telemt_upstream_connect_attempts_per_request{bucket="1"} 101960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 883
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4483
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1802
telemt_me_idle_close_by_peer_total 1802
telemt_me_route_drop_no_conn_total 4566262
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8871229
telemt_me_endpoint_quarantine_total 1330
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1498
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39078
telemt_desync_full_logged_total 13161
telemt_desync_suppressed_total 25917
telemt_desync_frames_bucket_total{bucket="1_2"} 9678
telemt_desync_frames_bucket_total{bucket="3_10"} 15006
telemt_desync_frames_bucket_total{bucket="gt_10"} 14394
telemt_pool_swap_total 209
telemt_pool_force_close_total 6228
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 715
telemt_me_draining_writers_reap_progress_total 65407
telemt_me_writer_removed_unexpected_total 1829
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5767
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59179
telemt_me_writer_teardown_success_total{mode="normal"} 67095
telemt_me_writer_teardown_noop_total 65432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132527
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.541964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132527
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 715
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1656
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 8808940
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 218256658396 (203.27 GB)
telemt_user_octets_to_client{user="hello"} 3980176247707 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 195673.7 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11127042
telemt_connections_bad_total 994022
telemt_connections_current 533
telemt_connections_me_current 533
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346250
telemt_upstream_connect_attempt_total 86878
telemt_upstream_connect_success_total 85314
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5804
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2169
telemt_me_idle_close_by_peer_total 2168
telemt_me_route_drop_no_conn_total 5345905
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8398489
telemt_me_endpoint_quarantine_total 1379
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1455
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
telemt_me_writers_active_current 44
telemt_desync_total 38302
telemt_desync_full_logged_total 12696
telemt_desync_suppressed_total 25606
telemt_desync_frames_bucket_total{bucket="1_2"} 9678
telemt_desync_frames_bucket_total{bucket="3_10"} 14662
telemt_desync_frames_bucket_total{bucket="gt_10"} 13962
telemt_pool_swap_total 205
telemt_pool_force_close_total 6122
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 747
telemt_me_draining_writers_reap_progress_total 65944
telemt_me_writer_removed_unexpected_total 2317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6518
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5551
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59822
telemt_me_writer_teardown_success_total{mode="normal"} 68195
telemt_me_writer_teardown_noop_total 66015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134210
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.870511
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134210
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 747
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 8390398
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 193076998227 (179.82 GB)
telemt_user_octets_to_client{user="hello"} 3483635532329 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65953.7 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11354712
telemt_connections_bad_total 670427
telemt_connections_current 1079
telemt_connections_me_current 1079
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 287073
telemt_upstream_connect_attempt_total 61341
telemt_upstream_connect_success_total 58166
telemt_upstream_connect_fail_total 2056
telemt_upstream_connect_attempts_per_request{bucket="1"} 60222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2056
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7887
telemt_me_reconnect_success_total 1335
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 869
telemt_me_route_drop_no_conn_total 25307261
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9414947
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 528
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
telemt_desync_total 16581
telemt_desync_full_logged_total 4556
telemt_desync_suppressed_total 12025
telemt_desync_frames_bucket_total{bucket="1_2"} 3160
telemt_desync_frames_bucket_total{bucket="3_10"} 6759
telemt_desync_frames_bucket_total{bucket="gt_10"} 6662
telemt_pool_swap_total 68
telemt_pool_force_close_total 2170
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 494
telemt_me_draining_writers_reap_progress_total 21610
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1849
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19440
telemt_me_writer_teardown_success_total{mode="normal"} 22780
telemt_me_writer_teardown_noop_total 21629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44409
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.023784
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44409
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 494
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 879
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 9440787
telemt_user_connections_current{user="hello"} 1079
telemt_user_octets_from_client{user="hello"} 87847950586 (81.81 GB)
telemt_user_octets_to_client{user="hello"} 633979048242 (590.44 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 195680.4 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11080370
telemt_connections_bad_total 966947
telemt_connections_current 909
telemt_connections_me_current 909
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244392
telemt_upstream_connect_attempt_total 115659
telemt_upstream_connect_success_total 114474
telemt_upstream_connect_fail_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 115484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1010
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73191
telemt_me_reconnect_success_total 3154
telemt_me_reader_eof_total 2851
telemt_me_idle_close_by_peer_total 2849
telemt_me_route_drop_no_conn_total 5274630
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8731368
telemt_me_endpoint_quarantine_total 1329
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1484
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
telemt_me_writers_active_current 45
telemt_desync_total 46554
telemt_desync_full_logged_total 15976
telemt_desync_suppressed_total 30578
telemt_desync_frames_bucket_total{bucket="1_2"} 9462
telemt_desync_frames_bucket_total{bucket="3_10"} 17822
telemt_desync_frames_bucket_total{bucket="gt_10"} 19270
telemt_pool_swap_total 201
telemt_pool_force_close_total 5838
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 69958
telemt_me_writer_removed_unexpected_total 2871
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65826
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5089
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64120
telemt_me_writer_teardown_success_total{mode="normal"} 72873
telemt_me_writer_teardown_noop_total 69959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.314783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2657
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8734235
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 196464068769 (182.97 GB)
telemt_user_octets_to_client{user="hello"} 3337213740760 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 132516.7 (36h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11796146
telemt_connections_bad_total 483867
telemt_connections_current 572
telemt_connections_me_current 572
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4781770
telemt_upstream_connect_attempt_total 64325
telemt_upstream_connect_success_total 63858
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 64312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_reconnect_attempts_total 49144
telemt_me_reconnect_success_total 1894
telemt_me_reader_eof_total 1569
telemt_me_idle_close_by_peer_total 1568
telemt_me_route_drop_no_conn_total 4103466
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5667407
telemt_me_endpoint_quarantine_total 909
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1020
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31871
telemt_desync_full_logged_total 10893
telemt_desync_suppressed_total 20978
telemt_desync_frames_bucket_total{bucket="1_2"} 6358
telemt_desync_frames_bucket_total{bucket="3_10"} 12578
telemt_desync_frames_bucket_total{bucket="gt_10"} 12935
telemt_pool_swap_total 141
telemt_pool_force_close_total 4050
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 49541
telemt_me_writer_removed_unexpected_total 1614
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47214
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3606
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45491
telemt_me_writer_teardown_success_total{mode="normal"} 51204
telemt_me_writer_teardown_noop_total 49548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.734848
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 2745
telemt_me_writer_restored_same_endpoint_total 1673
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5659489
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 120321453532 (112.06 GB)
telemt_user_octets_to_client{user="hello"} 2199172052442 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 113487.3 (31h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1568624
telemt_connections_bad_total 36943
telemt_connections_current 477
telemt_connections_me_current 477
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32295
telemt_upstream_connect_attempt_total 53795
telemt_upstream_connect_success_total 53626
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 53767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2329
telemt_me_reconnect_success_total 958
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 527922
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1394483
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 938
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 34
telemt_desync_total 9754
telemt_desync_full_logged_total 2766
telemt_desync_suppressed_total 6988
telemt_desync_frames_bucket_total{bucket="1_2"} 3003
telemt_desync_frames_bucket_total{bucket="3_10"} 3686
telemt_desync_frames_bucket_total{bucket="gt_10"} 3065
telemt_pool_swap_total 122
telemt_pool_force_close_total 3079
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 45685
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3458
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43182
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2991
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42606
telemt_me_writer_teardown_success_total{mode="normal"} 46640
telemt_me_writer_teardown_noop_total 45689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.429493
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1390237
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 26419663341 (24.61 GB)
telemt_user_octets_to_client{user="hello"} 588176592091 (547.78 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 195684.9 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13403429
telemt_connections_bad_total 1624438
telemt_connections_current 697
telemt_connections_me_current 697
telemt_handshake_timeouts_total 391479
telemt_upstream_connect_attempt_total 78232
telemt_upstream_connect_success_total 77877
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 78096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3074
telemt_me_reconnect_success_total 1551
telemt_me_reader_eof_total 1537
telemt_me_idle_close_by_peer_total 1537
telemt_me_route_drop_no_conn_total 4491281
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10092905
telemt_me_endpoint_quarantine_total 1429
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1483
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
telemt_me_writers_active_current 44
telemt_desync_total 42310
telemt_desync_full_logged_total 13820
telemt_desync_suppressed_total 28490
telemt_desync_frames_bucket_total{bucket="1_2"} 10285
telemt_desync_frames_bucket_total{bucket="3_10"} 15540
telemt_desync_frames_bucket_total{bucket="gt_10"} 16485
telemt_pool_swap_total 217
telemt_pool_force_close_total 5708
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 70789
telemt_me_writer_removed_unexpected_total 1472
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66812
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65081
telemt_me_writer_teardown_success_total{mode="normal"} 72316
telemt_me_writer_teardown_noop_total 70791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 140487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.839785
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1364
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10059543
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 195129748264 (181.73 GB)
telemt_user_octets_to_client{user="hello"} 4473571328548 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 195681.5 (54h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11708875
telemt_connections_bad_total 1368493
telemt_connections_current 687
telemt_connections_me_current 687
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313268
telemt_upstream_connect_attempt_total 105854
telemt_upstream_connect_success_total 104941
telemt_upstream_connect_fail_total 705
telemt_upstream_connect_attempts_per_request{bucket="1"} 105646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2068
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 705
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10753
telemt_me_reconnect_success_total 2661
telemt_me_reader_eof_total 2467
telemt_me_idle_close_by_peer_total 2466
telemt_me_seq_mismatch_total 102
telemt_me_route_drop_no_conn_total 5659012
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9009514
telemt_me_endpoint_quarantine_total 1605
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1488
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
telemt_desync_total 42074
telemt_desync_full_logged_total 13548
telemt_desync_suppressed_total 28526
telemt_desync_frames_bucket_total{bucket="1_2"} 10909
telemt_desync_frames_bucket_total{bucket="3_10"} 15470
telemt_desync_frames_bucket_total{bucket="gt_10"} 15695
telemt_pool_swap_total 207
telemt_pool_force_close_total 5476
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 70949
telemt_me_writer_removed_unexpected_total 2507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6887
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65473
telemt_me_writer_teardown_success_total{mode="normal"} 73547
telemt_me_writer_teardown_noop_total 70954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144501
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.526389
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144501
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 419
telemt_me_writer_restored_same_endpoint_total 2131
telemt_me_writer_restored_fallback_total 138
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9014073
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 157722766104 (146.89 GB)
telemt_user_octets_to_client{user="hello"} 3515879470826 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 94
```